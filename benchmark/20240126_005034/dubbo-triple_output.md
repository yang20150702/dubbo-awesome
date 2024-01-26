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
# Warmup Iteration   1: 4.901 ops/ms
# Warmup Iteration   2: 11.843 ops/ms
# Warmup Iteration   3: 12.234 ops/ms
Iteration   1: 12.640 ops/ms
Iteration   2: 12.706 ops/ms
Iteration   3: 12.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.651 ±(99.9%) 0.917 ops/ms [Average]
  (min, avg, max) = (12.608, 12.651, 12.706), stdev = 0.050
  CI (99.9%): [11.735, 13.568] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.422 ops/ms
# Warmup Iteration   2: 13.132 ops/ms
# Warmup Iteration   3: 12.967 ops/ms
Iteration   1: 13.104 ops/ms
Iteration   2: 13.026 ops/ms
Iteration   3: 13.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.052 ±(99.9%) 0.829 ops/ms [Average]
  (min, avg, max) = (13.025, 13.052, 13.104), stdev = 0.045
  CI (99.9%): [12.223, 13.881] (assumes normal distribution)


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
# Warmup Iteration   1: 7.758 ops/ms
# Warmup Iteration   2: 12.573 ops/ms
# Warmup Iteration   3: 12.770 ops/ms
Iteration   1: 12.841 ops/ms
Iteration   2: 12.840 ops/ms
Iteration   3: 12.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.832 ±(99.9%) 0.291 ops/ms [Average]
  (min, avg, max) = (12.813, 12.832, 12.841), stdev = 0.016
  CI (99.9%): [12.540, 13.123] (assumes normal distribution)


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
# Warmup Iteration   1: 7.059 ops/ms
# Warmup Iteration   2: 10.581 ops/ms
# Warmup Iteration   3: 10.619 ops/ms
Iteration   1: 10.769 ops/ms
Iteration   2: 10.734 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.726 ±(99.9%) 0.864 ops/ms [Average]
  (min, avg, max) = (10.675, 10.726, 10.769), stdev = 0.047
  CI (99.9%): [9.862, 11.590] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.002 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.003 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.500, 2.515, 2.534), stdev = 0.017
  CI (99.9%): [2.203, 2.826] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.400 ±(99.9%) 0.004 ms/op
Iteration   1: 2.401 ±(99.9%) 0.003 ms/op
Iteration   2: 2.424 ±(99.9%) 0.003 ms/op
Iteration   3: 2.401 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.409 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.401, 2.409, 2.424), stdev = 0.013
  CI (99.9%): [2.168, 2.650] (assumes normal distribution)


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.471, 2.490, 2.501), stdev = 0.017
  CI (99.9%): [2.183, 2.797] (assumes normal distribution)


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
Iteration   3: 2.986 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.011 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (2.986, 3.011, 3.031), stdev = 0.022
  CI (99.9%): [2.602, 3.420] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  11.138 ms/op
                 createUser·p0.9999: 13.976 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  8.844 ms/op
                 createUser·p0.9999: 11.881 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  8.159 ms/op
                 createUser·p0.9999: 12.878 ms/op
                 createUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384379
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 187313 
    [ 2.500,  3.750) = 193929 
    [ 3.750,  5.000) = 2197 
    [ 5.000,  6.250) = 399 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      8.164 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     14.687 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  7.815 ms/op
                 existUser·p0.9999: 13.567 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 12.422 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  8.105 ms/op
                 existUser·p0.9999: 11.108 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386878
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 188907 
    [ 2.500,  3.750) = 194523 
    [ 3.750,  5.000) = 2536 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      8.095 ms/op
     p(99.9900) =     12.812 ms/op
     p(99.9990) =     14.083 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.627 ms/op
                 getUser·p0.999:  10.044 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  5.936 ms/op
                 getUser·p0.9999: 12.505 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  8.408 ms/op
                 getUser·p0.9999: 12.337 ms/op
                 getUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383345
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 190621 
    [ 2.500,  3.750) = 188010 
    [ 3.750,  5.000) = 3477 
    [ 5.000,  6.250) = 757 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      6.717 ms/op
     p(99.9900) =     12.780 ms/op
     p(99.9990) =     13.667 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 4.505 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.008 ms/op
Iteration   1: 2.943 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 11.132 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.244 ms/op
                 listUser·p0.9999: 12.004 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 10.264 ms/op
                 listUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324034
  mean =      2.960 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 102557 
    [ 2.500,  3.750) = 184851 
    [ 3.750,  5.000) = 29766 
    [ 5.000,  6.250) = 5468 
    [ 6.250,  7.500) = 562 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     11.135 ms/op
     p(99.9990) =     12.380 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.651 ± 0.917  ops/ms
ClientPb.existUser                       thrpt       3  13.052 ± 0.829  ops/ms
ClientPb.getUser                         thrpt       3  12.832 ± 0.291  ops/ms
ClientPb.listUser                        thrpt       3  10.726 ± 0.864  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.311   ms/op
ClientPb.existUser                        avgt       3   2.409 ± 0.241   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.307   ms/op
ClientPb.listUser                         avgt       3   3.011 ± 0.409   ms/op
ClientPb.createUser                     sample  384379   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.922           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.164           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.091           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.352           ms/op
ClientPb.existUser                      sample  386878   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.908           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.095           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  383345   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.717           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.780           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.763           ms/op
ClientPb.listUser                       sample  324034   2.960 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.885           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.135           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
