# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.652 ops/ms
# Warmup Iteration   2: 6.172 ops/ms
# Warmup Iteration   3: 9.300 ops/ms
Iteration   1: 10.119 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.133 ±(99.9%) 2.716 ops/ms [Average]
  (min, avg, max) = (9.991, 10.133, 10.288), stdev = 0.149
  CI (99.9%): [7.417, 12.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.329 ops/ms
# Warmup Iteration   2: 9.362 ops/ms
# Warmup Iteration   3: 10.523 ops/ms
Iteration   1: 10.692 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.620 ±(99.9%) 1.143 ops/ms [Average]
  (min, avg, max) = (10.575, 10.620, 10.692), stdev = 0.063
  CI (99.9%): [9.478, 11.763] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ops/ms
# Warmup Iteration   2: 9.387 ops/ms
# Warmup Iteration   3: 9.843 ops/ms
Iteration   1: 10.213 ops/ms
Iteration   2: 10.214 ops/ms
Iteration   3: 9.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.081 ±(99.9%) 4.198 ops/ms [Average]
  (min, avg, max) = (9.815, 10.081, 10.214), stdev = 0.230
  CI (99.9%): [5.883, 14.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.576 ops/ms
# Warmup Iteration   2: 7.965 ops/ms
# Warmup Iteration   3: 8.562 ops/ms
Iteration   1: 8.751 ops/ms
Iteration   2: 8.742 ops/ms
Iteration   3: 8.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.718 ±(99.9%) 0.889 ops/ms [Average]
  (min, avg, max) = (8.662, 8.718, 8.751), stdev = 0.049
  CI (99.9%): [7.829, 9.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.707 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.003 ms/op
Iteration   1: 3.126 ±(99.9%) 0.005 ms/op
Iteration   2: 3.228 ±(99.9%) 0.004 ms/op
Iteration   3: 3.231 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.195 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.126, 3.195, 3.231), stdev = 0.060
  CI (99.9%): [2.107, 4.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.475 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.005 ms/op
Iteration   1: 3.087 ±(99.9%) 0.009 ms/op
Iteration   2: 3.190 ±(99.9%) 0.003 ms/op
Iteration   3: 3.030 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 1.485 ms/op [Average]
  (min, avg, max) = (3.030, 3.102, 3.190), stdev = 0.081
  CI (99.9%): [1.618, 4.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.825 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.003 ms/op
Iteration   1: 3.295 ±(99.9%) 0.005 ms/op
Iteration   2: 3.121 ±(99.9%) 0.004 ms/op
Iteration   3: 3.315 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.244 ±(99.9%) 1.947 ms/op [Average]
  (min, avg, max) = (3.121, 3.244, 3.315), stdev = 0.107
  CI (99.9%): [1.297, 5.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.213 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.005 ms/op
Iteration   1: 3.711 ±(99.9%) 0.010 ms/op
Iteration   2: 3.773 ±(99.9%) 0.006 ms/op
Iteration   3: 3.815 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.766 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (3.711, 3.766, 3.815), stdev = 0.053
  CI (99.9%): [2.808, 4.725] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.705 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.008 ms/op
Iteration   1: 3.258 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.842 ms/op
                 createUser·p0.999:  19.294 ms/op
                 createUser·p0.9999: 22.795 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.437 ms/op
                 createUser·p0.99:   5.277 ms/op
                 createUser·p0.999:  13.943 ms/op
                 createUser·p0.9999: 18.535 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305875
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23464 
    [ 2.500,  5.000) = 278423 
    [ 5.000,  7.500) = 3019 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     15.632 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.706 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.009 ms/op
Iteration   1: 3.036 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  13.353 ms/op
                 existUser·p0.9999: 24.366 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  12.337 ms/op
                 existUser·p0.9999: 19.364 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310838
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19733 
    [ 2.500,  5.000) = 285222 
    [ 5.000,  7.500) = 5042 
    [ 7.500, 10.000) = 328 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     12.340 ms/op
     p(99.9900) =     23.066 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.262 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
Iteration   1: 3.158 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  18.933 ms/op
                 getUser·p0.9999: 24.314 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  12.122 ms/op
                 getUser·p0.9999: 22.576 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.583 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  9.667 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301022
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7434 
    [ 2.500,  5.000) = 287992 
    [ 5.000,  7.500) = 4427 
    [ 7.500, 10.000) = 751 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     23.688 ms/op
     p(99.9990) =     24.868 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.467 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.012 ms/op
Iteration   1: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.310 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 21.284 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 3.727 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.061 ms/op
                 listUser·p0.9999: 16.719 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 3.751 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.870 ms/op
                 listUser·p0.999:  14.015 ms/op
                 listUser·p0.9999: 18.202 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255715
  mean =      3.752 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 248139 
    [ 5.000,  7.500) = 5448 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.133 ± 2.716  ops/ms
ClientPb.existUser                       thrpt       3  10.620 ± 1.143  ops/ms
ClientPb.getUser                         thrpt       3  10.081 ± 4.198  ops/ms
ClientPb.listUser                        thrpt       3   8.718 ± 0.889  ops/ms
ClientPb.createUser                       avgt       3   3.195 ± 1.089   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 1.485   ms/op
ClientPb.getUser                          avgt       3   3.244 ± 1.947   ms/op
ClientPb.listUser                         avgt       3   3.766 ± 0.959   ms/op
ClientPb.createUser                     sample  305875   3.137 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.632           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.856           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.543           ms/op
ClientPb.existUser                      sample  310838   3.087 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.340           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.066           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.330           ms/op
ClientPb.getUser                        sample  301022   3.187 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.016           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.812           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.688           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.100           ms/op
ClientPb.listUser                       sample  255715   3.752 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.185           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.822           ms/op
