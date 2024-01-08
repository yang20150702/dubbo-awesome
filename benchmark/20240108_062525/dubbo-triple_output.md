# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.112 ops/ms
# Warmup Iteration   2: 12.475 ops/ms
# Warmup Iteration   3: 12.543 ops/ms
Iteration   1: 12.779 ops/ms
Iteration   2: 12.910 ops/ms
Iteration   3: 12.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.893 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (12.779, 12.893, 12.990), stdev = 0.107
  CI (99.9%): [10.950, 14.837] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.170 ops/ms
# Warmup Iteration   2: 12.918 ops/ms
# Warmup Iteration   3: 13.084 ops/ms
Iteration   1: 13.246 ops/ms
Iteration   2: 13.136 ops/ms
Iteration   3: 13.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.168 ±(99.9%) 1.251 ops/ms [Average]
  (min, avg, max) = (13.121, 13.168, 13.246), stdev = 0.069
  CI (99.9%): [11.917, 14.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.755 ops/ms
# Warmup Iteration   2: 12.648 ops/ms
# Warmup Iteration   3: 12.983 ops/ms
Iteration   1: 13.034 ops/ms
Iteration   2: 12.981 ops/ms
Iteration   3: 12.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.955 ±(99.9%) 1.739 ops/ms [Average]
  (min, avg, max) = (12.849, 12.955, 13.034), stdev = 0.095
  CI (99.9%): [11.216, 14.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.657 ops/ms
# Warmup Iteration   2: 10.667 ops/ms
# Warmup Iteration   3: 10.721 ops/ms
Iteration   1: 10.813 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.811 ±(99.9%) 0.023 ops/ms [Average]
  (min, avg, max) = (10.810, 10.811, 10.813), stdev = 0.001
  CI (99.9%): [10.788, 10.834] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.003 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.477, 2.498, 2.511), stdev = 0.018
  CI (99.9%): [2.166, 2.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.575 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.003 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.456 ±(99.9%) 0.003 ms/op
Iteration   3: 2.450 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.422, 2.443, 2.456), stdev = 0.019
  CI (99.9%): [2.105, 2.781] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.461, 2.469, 2.484), stdev = 0.012
  CI (99.9%): [2.243, 2.695] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.392 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.005 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
Iteration   2: 3.007 ±(99.9%) 0.004 ms/op
Iteration   3: 2.984 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.984, 2.997, 3.007), stdev = 0.012
  CI (99.9%): [2.784, 3.210] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.396 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.701 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  12.003 ms/op
                 createUser·p0.9999: 13.934 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.476 ms/op
                 createUser·p0.9999: 12.389 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  8.844 ms/op
                 createUser·p0.9999: 11.578 ms/op
                 createUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382864
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 185116 
    [ 2.500,  3.750) = 193460 
    [ 3.750,  5.000) = 3427 
    [ 5.000,  6.250) = 276 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      9.636 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  5.221 ms/op
                 existUser·p0.9999: 14.269 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.783 ms/op
                 existUser·p0.999:  7.367 ms/op
                 existUser·p0.9999: 12.733 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.651 ms/op
                 existUser·p0.999:  8.468 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390606
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 194912 
    [ 2.500,  3.750) = 192603 
    [ 3.750,  5.000) = 2285 
    [ 5.000,  6.250) = 344 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     13.400 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 13.534 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.318 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 14.680 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  7.747 ms/op
                 getUser·p0.9999: 10.569 ms/op
                 getUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383156
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 190064 
    [ 2.500,  3.750) = 187351 
    [ 3.750,  5.000) = 4402 
    [ 5.000,  6.250) = 820 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     13.544 ms/op
     p(99.9990) =     14.896 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 12.927 ms/op
                 listUser·p1.00:   13.484 ms/op

Iteration   2: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 11.822 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.811 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320163
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 93769 
    [ 2.500,  3.750) = 188513 
    [ 3.750,  5.000) = 31404 
    [ 5.000,  6.250) = 5176 
    [ 6.250,  7.500) = 562 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     13.225 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.893 ± 1.944  ops/ms
ClientPb.existUser                       thrpt       3  13.168 ± 1.251  ops/ms
ClientPb.getUser                         thrpt       3  12.955 ± 1.739  ops/ms
ClientPb.listUser                        thrpt       3  10.811 ± 0.023  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.332   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.338   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.226   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.213   ms/op
ClientPb.createUser                     sample  382864   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.853           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.636           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.303           ms/op
ClientPb.existUser                      sample  390606   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.958           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.400           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.041           ms/op
ClientPb.getUser                        sample  383156   2.504 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.796           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.486           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.139           ms/op
ClientPb.listUser                       sample  320163   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.771           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
