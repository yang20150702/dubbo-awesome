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
# Warmup Iteration   1: 5.030 ops/ms
# Warmup Iteration   2: 12.817 ops/ms
# Warmup Iteration   3: 12.791 ops/ms
Iteration   1: 13.233 ops/ms
Iteration   2: 13.313 ops/ms
Iteration   3: 13.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.266 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (13.233, 13.266, 13.313), stdev = 0.042
  CI (99.9%): [12.501, 14.030] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.722 ops/ms
# Warmup Iteration   2: 13.227 ops/ms
# Warmup Iteration   3: 13.374 ops/ms
Iteration   1: 13.259 ops/ms
Iteration   2: 13.252 ops/ms
Iteration   3: 13.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.226 ±(99.9%) 0.956 ops/ms [Average]
  (min, avg, max) = (13.165, 13.226, 13.259), stdev = 0.052
  CI (99.9%): [12.270, 14.181] (assumes normal distribution)


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
# Warmup Iteration   1: 8.009 ops/ms
# Warmup Iteration   2: 12.858 ops/ms
# Warmup Iteration   3: 12.826 ops/ms
Iteration   1: 13.292 ops/ms
Iteration   2: 13.125 ops/ms
Iteration   3: 13.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.184 ±(99.9%) 1.707 ops/ms [Average]
  (min, avg, max) = (13.125, 13.184, 13.292), stdev = 0.094
  CI (99.9%): [11.477, 14.891] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.638 ops/ms
# Warmup Iteration   2: 10.580 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.693 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.689 ±(99.9%) 0.133 ops/ms [Average]
  (min, avg, max) = (10.681, 10.689, 10.694), stdev = 0.007
  CI (99.9%): [10.556, 10.822] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.004 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.501 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (2.481, 2.501, 2.524), stdev = 0.022
  CI (99.9%): [2.105, 2.898] (assumes normal distribution)


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
# Warmup Iteration   1: 3.556 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.401 ±(99.9%) 0.005 ms/op
Iteration   1: 2.395 ±(99.9%) 0.004 ms/op
Iteration   2: 2.379 ±(99.9%) 0.003 ms/op
Iteration   3: 2.377 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.384 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.377, 2.384, 2.395), stdev = 0.010
  CI (99.9%): [2.203, 2.564] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.003 ms/op
Iteration   3: 2.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.432 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.426, 2.432, 2.443), stdev = 0.009
  CI (99.9%): [2.269, 2.596] (assumes normal distribution)


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
Iteration   3: 2.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.964, 2.985, 3.005), stdev = 0.020
  CI (99.9%): [2.616, 3.355] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  5.726 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.482 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.060 ms/op
                 createUser·p0.99:   3.523 ms/op
                 createUser·p0.999:  5.507 ms/op
                 createUser·p0.9999: 12.532 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  9.286 ms/op
                 createUser·p0.9999: 12.222 ms/op
                 createUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 390491
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 193566 
    [ 2.500,  3.750) = 193575 
    [ 3.750,  5.000) = 2699 
    [ 5.000,  6.250) = 142 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      9.200 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.408 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.357 ±(99.9%) 0.005 ms/op
Iteration   1: 2.366 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.339 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  5.483 ms/op
                 existUser·p0.9999: 15.319 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   2: 2.388 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  6.970 ms/op
                 existUser·p0.9999: 13.805 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.375 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.367 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  6.309 ms/op
                 existUser·p0.9999: 11.314 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403554
  mean =      2.376 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 222102 
    [ 2.500,  3.750) = 177891 
    [ 3.750,  5.000) = 2774 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.367 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      6.670 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     15.434 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  5.985 ms/op
                 getUser·p0.9999: 14.746 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  7.971 ms/op
                 getUser·p0.9999: 12.714 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.429 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  5.922 ms/op
                 getUser·p0.9999: 10.465 ms/op
                 getUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 395353
  mean =      2.426 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 202430 
    [ 2.500,  3.750) = 189643 
    [ 3.750,  5.000) = 2512 
    [ 5.000,  6.250) = 261 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.132 ms/op
     p(99.9900) =     13.585 ms/op
     p(99.9990) =     15.354 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.575 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
Iteration   1: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.181 ms/op
                 listUser·p0.9999: 10.863 ms/op
                 listUser·p1.00:   13.599 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 12.096 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 13.902 ms/op
                 listUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322480
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 98389 
    [ 2.500,  3.750) = 186758 
    [ 3.750,  5.000) = 30093 
    [ 5.000,  6.250) = 5632 
    [ 6.250,  7.500) = 731 
    [ 7.500,  8.750) = 153 
    [ 8.750, 10.000) = 288 
    [10.000, 11.250) = 179 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     12.661 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.266 ± 0.764  ops/ms
ClientPb.existUser                       thrpt       3  13.226 ± 0.956  ops/ms
ClientPb.getUser                         thrpt       3  13.184 ± 1.707  ops/ms
ClientPb.listUser                        thrpt       3  10.689 ± 0.133  ops/ms
ClientPb.createUser                       avgt       3   2.501 ± 0.397   ms/op
ClientPb.existUser                        avgt       3   2.384 ± 0.181   ms/op
ClientPb.getUser                          avgt       3   2.432 ± 0.164   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.370   ms/op
ClientPb.createUser                     sample  390491   2.456 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.519           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.978           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.200           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.091           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.992           ms/op
ClientPb.existUser                      sample  403554   2.376 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.367           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.670           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.877           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.565           ms/op
ClientPb.getUser                        sample  395353   2.426 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.885           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.132           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.585           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.302           ms/op
ClientPb.listUser                       sample  322480   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.939           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.661           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.909           ms/op
