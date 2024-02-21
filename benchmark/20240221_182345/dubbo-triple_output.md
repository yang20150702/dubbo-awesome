# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.868 ops/ms
# Warmup Iteration   2: 11.766 ops/ms
# Warmup Iteration   3: 11.982 ops/ms
Iteration   1: 12.274 ops/ms
Iteration   2: 12.295 ops/ms
Iteration   3: 12.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.324 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (12.274, 12.324, 12.405), stdev = 0.070
  CI (99.9%): [11.041, 13.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.244 ops/ms
# Warmup Iteration   2: 12.944 ops/ms
# Warmup Iteration   3: 12.879 ops/ms
Iteration   1: 12.945 ops/ms
Iteration   2: 12.895 ops/ms
Iteration   3: 12.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.883 ±(99.9%) 1.262 ops/ms [Average]
  (min, avg, max) = (12.808, 12.883, 12.945), stdev = 0.069
  CI (99.9%): [11.621, 14.145] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.927 ops/ms
# Warmup Iteration   2: 12.634 ops/ms
# Warmup Iteration   3: 12.606 ops/ms
Iteration   1: 12.794 ops/ms
Iteration   2: 12.741 ops/ms
Iteration   3: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.772 ±(99.9%) 0.506 ops/ms [Average]
  (min, avg, max) = (12.741, 12.772, 12.794), stdev = 0.028
  CI (99.9%): [12.266, 13.277] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.775 ops/ms
# Warmup Iteration   2: 10.387 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.573 ops/ms
Iteration   3: 10.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.564 ±(99.9%) 0.295 ops/ms [Average]
  (min, avg, max) = (10.545, 10.564, 10.574), stdev = 0.016
  CI (99.9%): [10.269, 10.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.553 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (2.549, 2.553, 2.560), stdev = 0.006
  CI (99.9%): [2.445, 2.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.003 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (2.447, 2.453, 2.460), stdev = 0.007
  CI (99.9%): [2.329, 2.577] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.003 ms/op
Iteration   2: 2.492 ±(99.9%) 0.003 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.505 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.492, 2.505, 2.525), stdev = 0.017
  CI (99.9%): [2.187, 2.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.712 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
Iteration   3: 3.008 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.983 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.962, 2.983, 3.008), stdev = 0.023
  CI (99.9%): [2.561, 3.406] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  10.803 ms/op
                 createUser·p0.9999: 13.582 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 13.375 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  8.245 ms/op
                 createUser·p0.9999: 9.634 ms/op
                 createUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379152
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 184323 
    [ 2.500,  3.750) = 190883 
    [ 3.750,  5.000) = 2982 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 143 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.333 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.338 ms/op
                 existUser·p0.999:  5.728 ms/op
                 existUser·p0.9999: 13.058 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  7.185 ms/op
                 existUser·p0.9999: 12.714 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  8.017 ms/op
                 existUser·p0.9999: 17.336 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390562
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 191145 
    [ 2.500,  3.750) = 196079 
    [ 3.750,  5.000) = 2481 
    [ 5.000,  6.250) = 388 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.675 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.797 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  11.622 ms/op
                 getUser·p0.9999: 14.041 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.184 ms/op
                 getUser·p0.999:  9.370 ms/op
                 getUser·p0.9999: 13.161 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  7.609 ms/op
                 getUser·p0.9999: 11.723 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383389
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 191020 
    [ 2.500,  3.750) = 187571 
    [ 3.750,  5.000) = 3218 
    [ 5.000,  6.250) = 1060 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      7.992 ms/op
     p(99.9900) =     13.626 ms/op
     p(99.9990) =     14.858 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.733 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.617 ms/op
                 listUser·p0.999:  9.035 ms/op
                 listUser·p0.9999: 10.210 ms/op
                 listUser·p1.00:   10.568 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 10.474 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 11.222 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315114
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 85934 
    [ 2.500,  3.750) = 187528 
    [ 3.750,  5.000) = 34403 
    [ 5.000,  6.250) = 5784 
    [ 6.250,  7.500) = 712 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 321 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     10.682 ms/op
     p(99.9990) =     11.576 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.324 ± 1.283  ops/ms
ClientPb.existUser                       thrpt       3  12.883 ± 1.262  ops/ms
ClientPb.getUser                         thrpt       3  12.772 ± 0.506  ops/ms
ClientPb.listUser                        thrpt       3  10.564 ± 0.295  ops/ms
ClientPb.createUser                       avgt       3   2.553 ± 0.109   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.124   ms/op
ClientPb.getUser                          avgt       3   2.505 ± 0.318   ms/op
ClientPb.listUser                         avgt       3   2.983 ± 0.423   ms/op
ClientPb.createUser                     sample  379152   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.894           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.333           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.369           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.303           ms/op
ClientPb.existUser                      sample  390562   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.675           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.353           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.531           ms/op
ClientPb.getUser                        sample  383389   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.808           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.992           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.626           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.106           ms/op
ClientPb.listUser                       sample  315114   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.878           ms/op
