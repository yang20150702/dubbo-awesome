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
# Warmup Iteration   1: 4.339 ops/ms
# Warmup Iteration   2: 12.069 ops/ms
# Warmup Iteration   3: 12.122 ops/ms
Iteration   1: 12.621 ops/ms
Iteration   2: 12.522 ops/ms
Iteration   3: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.620 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (12.522, 12.620, 12.718), stdev = 0.098
  CI (99.9%): [10.830, 14.410] (assumes normal distribution)


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
# Warmup Iteration   1: 8.220 ops/ms
# Warmup Iteration   2: 13.058 ops/ms
# Warmup Iteration   3: 12.807 ops/ms
Iteration   1: 13.047 ops/ms
Iteration   2: 13.120 ops/ms
Iteration   3: 13.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.060 ±(99.9%) 0.996 ops/ms [Average]
  (min, avg, max) = (13.014, 13.060, 13.120), stdev = 0.055
  CI (99.9%): [12.064, 14.057] (assumes normal distribution)


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
# Warmup Iteration   1: 7.401 ops/ms
# Warmup Iteration   2: 12.482 ops/ms
# Warmup Iteration   3: 12.755 ops/ms
Iteration   1: 12.733 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.826 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (12.733, 12.826, 12.895), stdev = 0.083
  CI (99.9%): [11.306, 14.345] (assumes normal distribution)


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
# Warmup Iteration   1: 6.541 ops/ms
# Warmup Iteration   2: 10.275 ops/ms
# Warmup Iteration   3: 10.413 ops/ms
Iteration   1: 10.448 ops/ms
Iteration   2: 10.468 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.463 ±(99.9%) 0.251 ops/ms [Average]
  (min, avg, max) = (10.448, 10.463, 10.474), stdev = 0.014
  CI (99.9%): [10.213, 10.714] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.653 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.568 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.003 ms/op
Iteration   3: 2.531 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.521, 2.540, 2.568), stdev = 0.025
  CI (99.9%): [2.086, 2.994] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.449 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.449, 2.467, 2.479), stdev = 0.016
  CI (99.9%): [2.173, 2.761] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.003 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.499, 2.506, 2.519), stdev = 0.012
  CI (99.9%): [2.296, 2.716] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.719 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.004 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
Iteration   3: 3.061 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.066 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (3.061, 3.066, 3.075), stdev = 0.008
  CI (99.9%): [2.929, 3.204] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.094 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  12.310 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  10.522 ms/op
                 createUser·p0.9999: 13.435 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  8.392 ms/op
                 createUser·p0.9999: 10.376 ms/op
                 createUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383845
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186987 
    [ 2.500,  5.000) = 196036 
    [ 5.000,  7.500) = 406 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     15.158 ms/op
     p(99.9990) =     25.001 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  8.087 ms/op
                 existUser·p0.9999: 14.582 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  5.601 ms/op
                 existUser·p0.9999: 14.142 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  9.542 ms/op
                 existUser·p0.9999: 12.364 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385247
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 190666 
    [ 2.500,  3.750) = 190335 
    [ 3.750,  5.000) = 3224 
    [ 5.000,  6.250) = 561 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      7.117 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     14.676 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.930 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  11.520 ms/op
                 getUser·p0.9999: 13.527 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  9.895 ms/op
                 getUser·p0.9999: 13.468 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.529 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  8.538 ms/op
                 getUser·p0.9999: 11.076 ms/op
                 getUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381799
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 188968 
    [ 2.500,  3.750) = 188524 
    [ 3.750,  5.000) = 3348 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.588 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.227 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.115 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.009 ms/op
Iteration   1: 3.141 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  9.293 ms/op
                 listUser·p0.9999: 11.040 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  10.195 ms/op
                 listUser·p0.9999: 12.000 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   3: 3.087 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.654 ms/op
                 listUser·p0.999:  10.083 ms/op
                 listUser·p0.9999: 11.873 ms/op
                 listUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308140
  mean =      3.113 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 72211 
    [ 2.500,  3.750) = 189647 
    [ 3.750,  5.000) = 37680 
    [ 5.000,  6.250) = 6870 
    [ 6.250,  7.500) = 942 
    [ 7.500,  8.750) = 169 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 244 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     11.753 ms/op
     p(99.9990) =     12.435 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.620 ± 1.790  ops/ms
ClientPb.existUser                       thrpt       3  13.060 ± 0.996  ops/ms
ClientPb.getUser                         thrpt       3  12.826 ± 1.520  ops/ms
ClientPb.listUser                        thrpt       3  10.463 ± 0.251  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.454   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.294   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.210   ms/op
ClientPb.listUser                         avgt       3   3.066 ± 0.137   ms/op
ClientPb.createUser                     sample  383845   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.965           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.667           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.158           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.362           ms/op
ClientPb.existUser                      sample  385247   2.490 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.117           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.877           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.778           ms/op
ClientPb.getUser                        sample  381799   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.842           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.588           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.238           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.369           ms/op
ClientPb.listUser                       sample  308140   3.113 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.994           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.753           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.468           ms/op
