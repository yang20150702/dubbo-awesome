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
# Warmup Iteration   1: 4.586 ops/ms
# Warmup Iteration   2: 12.099 ops/ms
# Warmup Iteration   3: 12.526 ops/ms
Iteration   1: 12.789 ops/ms
Iteration   2: 12.722 ops/ms
Iteration   3: 12.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.776 ±(99.9%) 0.891 ops/ms [Average]
  (min, avg, max) = (12.722, 12.776, 12.817), stdev = 0.049
  CI (99.9%): [11.885, 13.667] (assumes normal distribution)


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
# Warmup Iteration   1: 8.756 ops/ms
# Warmup Iteration   2: 13.319 ops/ms
# Warmup Iteration   3: 13.291 ops/ms
Iteration   1: 13.484 ops/ms
Iteration   2: 13.491 ops/ms
Iteration   3: 13.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.461 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (13.408, 13.461, 13.491), stdev = 0.046
  CI (99.9%): [12.623, 14.299] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.911 ops/ms
# Warmup Iteration   2: 12.783 ops/ms
# Warmup Iteration   3: 13.112 ops/ms
Iteration   1: 13.182 ops/ms
Iteration   2: 13.139 ops/ms
Iteration   3: 13.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.155 ±(99.9%) 0.427 ops/ms [Average]
  (min, avg, max) = (13.139, 13.155, 13.182), stdev = 0.023
  CI (99.9%): [12.729, 13.582] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.819 ops/ms
# Warmup Iteration   2: 10.786 ops/ms
# Warmup Iteration   3: 10.943 ops/ms
Iteration   1: 10.844 ops/ms
Iteration   2: 10.840 ops/ms
Iteration   3: 10.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.875 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (10.840, 10.875, 10.940), stdev = 0.056
  CI (99.9%): [9.844, 11.905] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (2.467, 2.491, 2.522), stdev = 0.028
  CI (99.9%): [1.984, 2.999] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.486 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.378 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.393 ±(99.9%) 0.004 ms/op
Iteration   3: 2.392 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.406 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (2.392, 2.406, 2.434), stdev = 0.024
  CI (99.9%): [1.972, 2.840] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.745 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.003 ms/op
Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
Iteration   3: 2.485 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.456, 2.470, 2.485), stdev = 0.014
  CI (99.9%): [2.206, 2.735] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.526 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.004 ms/op
Iteration   1: 2.929 ±(99.9%) 0.004 ms/op
Iteration   2: 2.934 ±(99.9%) 0.004 ms/op
Iteration   3: 2.931 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.931 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.929, 2.931, 2.934), stdev = 0.003
  CI (99.9%): [2.884, 2.979] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  6.765 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.531 ms/op
                 createUser·p0.999:  5.841 ms/op
                 createUser·p0.9999: 12.270 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.749 ms/op
                 createUser·p0.999:  8.331 ms/op
                 createUser·p0.9999: 10.535 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 390943
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 191737 
    [ 2.500,  3.750) = 195523 
    [ 3.750,  5.000) = 2688 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 153 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.323 ms/op
     p(99.9900) =     12.826 ms/op
     p(99.9990) =     13.535 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.382 ±(99.9%) 0.005 ms/op
Iteration   1: 2.391 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  4.975 ms/op
                 existUser·p0.9999: 13.287 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  6.125 ms/op
                 existUser·p0.9999: 13.119 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  7.882 ms/op
                 existUser·p0.9999: 11.567 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399656
  mean =      2.400 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 203285 
    [ 2.500,  3.750) = 193428 
    [ 3.750,  5.000) = 2222 
    [ 5.000,  6.250) = 282 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      5.582 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     13.714 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.506 ms/op
                 getUser·p0.999:  7.571 ms/op
                 getUser·p0.9999: 13.652 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  8.436 ms/op
                 getUser·p0.9999: 16.665 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  7.868 ms/op
                 getUser·p0.9999: 11.895 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387182
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 193044 
    [ 2.500,  3.750) = 190013 
    [ 3.750,  5.000) = 3222 
    [ 5.000,  6.250) = 392 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      7.771 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     18.027 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.008 ms/op
Iteration   1: 2.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.217 ms/op
                 listUser·p0.9999: 9.964 ms/op
                 listUser·p1.00:   10.191 ms/op

Iteration   2: 2.941 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.744 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.315 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 10.439 ms/op
                 listUser·p1.00:   10.879 ms/op

Iteration   3: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 12.652 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324982
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 101163 
    [ 2.500,  3.750) = 189061 
    [ 3.750,  5.000) = 28245 
    [ 5.000,  6.250) = 5100 
    [ 6.250,  7.500) = 587 
    [ 7.500,  8.750) = 313 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.674 ms/op
     p(99.9990) =     12.816 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.776 ± 0.891  ops/ms
ClientPb.existUser                       thrpt       3  13.461 ± 0.838  ops/ms
ClientPb.getUser                         thrpt       3  13.155 ± 0.427  ops/ms
ClientPb.listUser                        thrpt       3  10.875 ± 1.031  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.508   ms/op
ClientPb.existUser                        avgt       3   2.406 ± 0.434   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.264   ms/op
ClientPb.listUser                         avgt       3   2.931 ± 0.048   ms/op
ClientPb.createUser                     sample  390943   2.453 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.837           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.323           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.826           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.891           ms/op
ClientPb.existUser                      sample  399656   2.400 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.124           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  387182   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.771           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.992           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.186           ms/op
ClientPb.listUser                       sample  324982   2.951 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.674           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.993           ms/op
