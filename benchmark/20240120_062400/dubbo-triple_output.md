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
# Warmup Iteration   1: 5.393 ops/ms
# Warmup Iteration   2: 12.057 ops/ms
# Warmup Iteration   3: 12.319 ops/ms
Iteration   1: 12.596 ops/ms
Iteration   2: 12.765 ops/ms
Iteration   3: 12.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.706 ±(99.9%) 1.744 ops/ms [Average]
  (min, avg, max) = (12.596, 12.706, 12.765), stdev = 0.096
  CI (99.9%): [10.962, 14.450] (assumes normal distribution)


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
# Warmup Iteration   1: 8.495 ops/ms
# Warmup Iteration   2: 13.128 ops/ms
# Warmup Iteration   3: 13.291 ops/ms
Iteration   1: 13.233 ops/ms
Iteration   2: 13.228 ops/ms
Iteration   3: 13.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.213 ±(99.9%) 0.568 ops/ms [Average]
  (min, avg, max) = (13.177, 13.213, 13.233), stdev = 0.031
  CI (99.9%): [12.645, 13.780] (assumes normal distribution)


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
# Warmup Iteration   1: 8.165 ops/ms
# Warmup Iteration   2: 12.491 ops/ms
# Warmup Iteration   3: 12.800 ops/ms
Iteration   1: 12.893 ops/ms
Iteration   2: 12.810 ops/ms
Iteration   3: 12.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.879 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (12.810, 12.879, 12.934), stdev = 0.063
  CI (99.9%): [11.724, 14.034] (assumes normal distribution)


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
# Warmup Iteration   1: 6.812 ops/ms
# Warmup Iteration   2: 10.577 ops/ms
# Warmup Iteration   3: 10.720 ops/ms
Iteration   1: 10.667 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.644 ±(99.9%) 0.359 ops/ms [Average]
  (min, avg, max) = (10.631, 10.644, 10.667), stdev = 0.020
  CI (99.9%): [10.285, 11.004] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.003 ms/op
Iteration   2: 2.543 ±(99.9%) 0.003 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (2.478, 2.509, 2.543), stdev = 0.033
  CI (99.9%): [1.909, 3.110] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
Iteration   3: 2.462 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.447, 2.458, 2.464), stdev = 0.010
  CI (99.9%): [2.284, 2.632] (assumes normal distribution)


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.877 ms/op [Average]
  (min, avg, max) = (2.465, 2.509, 2.560), stdev = 0.048
  CI (99.9%): [1.632, 3.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
Iteration   3: 3.023 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (3.013, 3.026, 3.041), stdev = 0.014
  CI (99.9%): [2.771, 3.280] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.043 ms/op
                 createUser·p0.999:  10.568 ms/op
                 createUser·p0.9999: 15.229 ms/op
                 createUser·p1.00:   15.892 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  9.089 ms/op
                 createUser·p0.9999: 12.177 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.364 ms/op
                 createUser·p0.9999: 10.786 ms/op
                 createUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379084
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 183509 
    [ 2.500,  3.750) = 191370 
    [ 3.750,  5.000) = 3243 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     12.979 ms/op
     p(99.9990) =     15.880 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.489 ms/op
                 existUser·p0.9999: 15.190 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  7.892 ms/op
                 existUser·p0.9999: 15.137 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  8.405 ms/op
                 existUser·p0.9999: 12.141 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390185
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 193073 
    [ 2.500,  3.750) = 194030 
    [ 3.750,  5.000) = 2193 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      7.599 ms/op
     p(99.9900) =     14.646 ms/op
     p(99.9990) =     16.009 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
Iteration   1: 2.552 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.970 ms/op
                 getUser·p0.999:  5.628 ms/op
                 getUser·p0.9999: 13.115 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 2.625 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.207 ms/op
                 getUser·p0.95:   3.420 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 14.245 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  9.078 ms/op
                 getUser·p0.9999: 11.977 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 371964
  mean =      2.579 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 177596 
    [ 2.500,  3.750) = 187023 
    [ 3.750,  5.000) = 5427 
    [ 5.000,  6.250) = 1427 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     14.783 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.663 ms/op
                 listUser·p0.9999: 10.910 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.555 ms/op
                 listUser·p0.9999: 11.322 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   3: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.382 ms/op
                 listUser·p0.9999: 11.910 ms/op
                 listUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314315
  mean =      3.052 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 86431 
    [ 2.500,  3.750) = 185579 
    [ 3.750,  5.000) = 34079 
    [ 5.000,  6.250) = 6805 
    [ 6.250,  7.500) = 675 
    [ 7.500,  8.750) = 216 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.429 ms/op
     p(99.9990) =     12.782 ms/op
     p(99.9999) =     12.861 ms/op
    p(100.0000) =     12.861 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.706 ± 1.744  ops/ms
ClientPb.existUser                       thrpt       3  13.213 ± 0.568  ops/ms
ClientPb.getUser                         thrpt       3  12.879 ± 1.155  ops/ms
ClientPb.listUser                        thrpt       3  10.644 ± 0.359  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.600   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.174   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.877   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.254   ms/op
ClientPb.createUser                     sample  379084   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.866           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.979           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.892           ms/op
ClientPb.existUser                      sample  390185   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.567           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.646           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.155           ms/op
ClientPb.getUser                        sample  371964   2.579 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.715           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.605           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.044           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.254           ms/op
ClientPb.listUser                       sample  314315   3.052 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.842           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.429           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.861           ms/op
