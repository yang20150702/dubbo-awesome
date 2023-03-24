# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.789 ops/ms
# Warmup Iteration   2: 4.159 ops/ms
# Warmup Iteration   3: 8.471 ops/ms
Iteration   1: 8.503 ops/ms
Iteration   2: 9.098 ops/ms
Iteration   3: 8.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.800 ±(99.9%) 5.427 ops/ms [Average]
  (min, avg, max) = (8.503, 8.800, 9.098), stdev = 0.297
  CI (99.9%): [3.373, 14.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.338 ops/ms
# Warmup Iteration   2: 7.730 ops/ms
# Warmup Iteration   3: 9.280 ops/ms
Iteration   1: 9.982 ops/ms
Iteration   2: 9.883 ops/ms
Iteration   3: 9.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.866 ±(99.9%) 2.292 ops/ms [Average]
  (min, avg, max) = (9.733, 9.866, 9.982), stdev = 0.126
  CI (99.9%): [7.574, 12.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.795 ops/ms
# Warmup Iteration   2: 8.296 ops/ms
# Warmup Iteration   3: 8.798 ops/ms
Iteration   1: 9.176 ops/ms
Iteration   2: 9.358 ops/ms
Iteration   3: 9.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.315 ±(99.9%) 2.254 ops/ms [Average]
  (min, avg, max) = (9.176, 9.315, 9.411), stdev = 0.124
  CI (99.9%): [7.061, 11.569] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.753 ops/ms
# Warmup Iteration   2: 7.243 ops/ms
# Warmup Iteration   3: 7.721 ops/ms
Iteration   1: 7.877 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 8.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.072 ±(99.9%) 4.323 ops/ms [Average]
  (min, avg, max) = (7.877, 8.072, 8.336), stdev = 0.237
  CI (99.9%): [3.749, 12.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.774 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.004 ms/op
Iteration   1: 3.451 ±(99.9%) 0.007 ms/op
Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
Iteration   3: 3.427 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.428 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.407, 3.428, 3.451), stdev = 0.022
  CI (99.9%): [3.027, 3.829] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.893 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
Iteration   1: 3.358 ±(99.9%) 0.005 ms/op
Iteration   2: 3.281 ±(99.9%) 0.005 ms/op
Iteration   3: 3.241 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.293 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (3.241, 3.293, 3.358), stdev = 0.060
  CI (99.9%): [2.203, 4.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.825 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.008 ms/op
Iteration   1: 3.492 ±(99.9%) 0.007 ms/op
Iteration   2: 3.569 ±(99.9%) 0.005 ms/op
Iteration   3: 3.804 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.621 ±(99.9%) 2.964 ms/op [Average]
  (min, avg, max) = (3.492, 3.621, 3.804), stdev = 0.162
  CI (99.9%): [0.657, 6.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.202 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
Iteration   1: 3.908 ±(99.9%) 0.012 ms/op
Iteration   2: 3.848 ±(99.9%) 0.015 ms/op
Iteration   3: 3.831 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.862 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.831, 3.862, 3.908), stdev = 0.040
  CI (99.9%): [3.124, 4.601] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.285 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.011 ms/op
Iteration   1: 3.340 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  19.949 ms/op
                 createUser·p0.9999: 32.364 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   2: 3.383 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.765 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.408 ms/op
                 createUser·p0.999:  20.710 ms/op
                 createUser·p0.9999: 26.654 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.568 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  16.885 ms/op
                 createUser·p0.9999: 26.870 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280144
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10382 
    [ 2.500,  5.000) = 263336 
    [ 5.000,  7.500) = 5146 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     16.997 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     32.676 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.010 ms/op
Iteration   1: 3.265 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  14.861 ms/op
                 existUser·p0.9999: 23.449 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   2: 3.253 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  11.301 ms/op
                 existUser·p0.9999: 27.525 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 3.251 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  15.284 ms/op
                 existUser·p0.9999: 28.317 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294526
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5757 
    [ 2.500,  5.000) = 283687 
    [ 5.000,  7.500) = 4054 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     27.692 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.010 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
Iteration   1: 3.487 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  21.472 ms/op
                 getUser·p0.9999: 33.603 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  24.330 ms/op
                 getUser·p0.9999: 27.406 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 3.409 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.763 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  24.969 ms/op
                 getUser·p0.9999: 28.594 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278714
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9528 
    [ 2.500,  5.000) = 261237 
    [ 5.000,  7.500) = 6911 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 152 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     21.973 ms/op
     p(99.9900) =     32.473 ms/op
     p(99.9990) =     33.699 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.846 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.015 ms/op
Iteration   1: 4.066 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  22.053 ms/op
                 listUser·p0.9999: 26.163 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 4.070 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  16.276 ms/op
                 listUser·p0.9999: 21.697 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 3.949 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 15.499 ms/op
                 listUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238189
  mean =      4.027 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 230367 
    [ 5.000,  7.500) = 5679 
    [ 7.500, 10.000) = 1284 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     16.057 ms/op
     p(99.9900) =     24.731 ms/op
     p(99.9990) =     27.389 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.800 ± 5.427  ops/ms
ClientPb.existUser                       thrpt       3   9.866 ± 2.292  ops/ms
ClientPb.getUser                         thrpt       3   9.315 ± 2.254  ops/ms
ClientPb.listUser                        thrpt       3   8.072 ± 4.323  ops/ms
ClientPb.createUser                       avgt       3   3.428 ± 0.401   ms/op
ClientPb.existUser                        avgt       3   3.293 ± 1.091   ms/op
ClientPb.getUser                          avgt       3   3.621 ± 2.964   ms/op
ClientPb.listUser                         avgt       3   3.862 ± 0.738   ms/op
ClientPb.createUser                     sample  280144   3.427 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.103           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.997           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.983           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.965           ms/op
ClientPb.existUser                      sample  294526   3.256 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.430           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.860           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.692           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.721           ms/op
ClientPb.getUser                        sample  278714   3.441 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.391           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.382           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.973           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.473           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  238189   4.027 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.057           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.731           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.820           ms/op
