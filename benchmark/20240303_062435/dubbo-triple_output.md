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
# Warmup Iteration   1: 4.959 ops/ms
# Warmup Iteration   2: 12.257 ops/ms
# Warmup Iteration   3: 12.693 ops/ms
Iteration   1: 12.968 ops/ms
Iteration   2: 13.081 ops/ms
Iteration   3: 12.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.013 ±(99.9%) 1.104 ops/ms [Average]
  (min, avg, max) = (12.968, 13.013, 13.081), stdev = 0.061
  CI (99.9%): [11.908, 14.117] (assumes normal distribution)


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
# Warmup Iteration   1: 8.548 ops/ms
# Warmup Iteration   2: 13.312 ops/ms
# Warmup Iteration   3: 13.376 ops/ms
Iteration   1: 13.393 ops/ms
Iteration   2: 13.440 ops/ms
Iteration   3: 13.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.425 ±(99.9%) 0.499 ops/ms [Average]
  (min, avg, max) = (13.393, 13.425, 13.442), stdev = 0.027
  CI (99.9%): [12.926, 13.924] (assumes normal distribution)


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
# Warmup Iteration   1: 8.141 ops/ms
# Warmup Iteration   2: 12.847 ops/ms
# Warmup Iteration   3: 13.035 ops/ms
Iteration   1: 13.115 ops/ms
Iteration   2: 12.946 ops/ms
Iteration   3: 12.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.972 ±(99.9%) 2.403 ops/ms [Average]
  (min, avg, max) = (12.856, 12.972, 13.115), stdev = 0.132
  CI (99.9%): [10.570, 15.375] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.798 ops/ms
# Warmup Iteration   2: 10.507 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.703 ops/ms
Iteration   2: 10.553 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.653 ±(99.9%) 1.587 ops/ms [Average]
  (min, avg, max) = (10.553, 10.653, 10.704), stdev = 0.087
  CI (99.9%): [9.066, 12.240] (assumes normal distribution)


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.482, 2.494, 2.509), stdev = 0.014
  CI (99.9%): [2.248, 2.741] (assumes normal distribution)


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.397 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.387 ±(99.9%) 0.003 ms/op
Iteration   1: 2.390 ±(99.9%) 0.003 ms/op
Iteration   2: 2.382 ±(99.9%) 0.003 ms/op
Iteration   3: 2.382 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.385 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (2.382, 2.385, 2.390), stdev = 0.005
  CI (99.9%): [2.302, 2.468] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.003 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (2.463, 2.467, 2.472), stdev = 0.005
  CI (99.9%): [2.377, 2.556] (assumes normal distribution)


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.005 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
Iteration   2: 2.942 ±(99.9%) 0.006 ms/op
Iteration   3: 2.936 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.938 ±(99.9%) 0.063 ms/op [Average]
  (min, avg, max) = (2.936, 2.938, 2.942), stdev = 0.003
  CI (99.9%): [2.875, 3.001] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.037 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  6.954 ms/op
                 createUser·p0.9999: 13.846 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  6.531 ms/op
                 createUser·p0.9999: 11.376 ms/op
                 createUser·p1.00:   11.731 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.091 ms/op
                 createUser·p0.99:   3.628 ms/op
                 createUser·p0.999:  8.569 ms/op
                 createUser·p0.9999: 10.503 ms/op
                 createUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388175
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 190497 
    [ 2.500,  3.750) = 194588 
    [ 3.750,  5.000) = 2282 
    [ 5.000,  6.250) = 321 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     12.881 ms/op
     p(99.9990) =     14.078 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.557 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
Iteration   1: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  7.624 ms/op
                 existUser·p0.9999: 13.097 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  5.325 ms/op
                 existUser·p0.9999: 10.928 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  8.225 ms/op
                 existUser·p0.9999: 11.796 ms/op
                 existUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397020
  mean =      2.416 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 204325 
    [ 2.500,  3.750) = 188901 
    [ 3.750,  5.000) = 2998 
    [ 5.000,  6.250) = 284 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      7.233 ms/op
     p(99.9900) =     12.757 ms/op
     p(99.9990) =     13.764 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  6.744 ms/op
                 getUser·p0.9999: 13.337 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  6.197 ms/op
                 getUser·p0.9999: 11.583 ms/op
                 getUser·p1.00:   12.141 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  5.594 ms/op
                 getUser·p0.9999: 12.532 ms/op
                 getUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391550
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 199951 
    [ 2.500,  3.750) = 186754 
    [ 3.750,  5.000) = 3759 
    [ 5.000,  6.250) = 613 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      6.189 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 12.472 ms/op
                 listUser·p1.00:   12.648 ms/op

Iteration   2: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.204 ms/op
                 listUser·p0.9999: 11.272 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.605 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322568
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 100567 
    [ 2.500,  3.750) = 184317 
    [ 3.750,  5.000) = 30217 
    [ 5.000,  6.250) = 5987 
    [ 6.250,  7.500) = 590 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 303 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.301 ms/op
     p(99.9990) =     12.563 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.013 ± 1.104  ops/ms
ClientPb.existUser                       thrpt       3  13.425 ± 0.499  ops/ms
ClientPb.getUser                         thrpt       3  12.972 ± 2.403  ops/ms
ClientPb.listUser                        thrpt       3  10.653 ± 1.587  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.247   ms/op
ClientPb.existUser                        avgt       3   2.385 ± 0.083   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.090   ms/op
ClientPb.listUser                         avgt       3   2.938 ± 0.063   ms/op
ClientPb.createUser                     sample  388175   2.471 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.881           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.189           ms/op
ClientPb.existUser                      sample  397020   2.416 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.449           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.233           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.757           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  391550   2.449 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.652           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.189           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.124           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.681           ms/op
ClientPb.listUser                       sample  322568   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.301           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.648           ms/op
