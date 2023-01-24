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
# Warmup Iteration   1: 2.649 ops/ms
# Warmup Iteration   2: 5.529 ops/ms
# Warmup Iteration   3: 9.475 ops/ms
Iteration   1: 9.730 ops/ms
Iteration   2: 9.628 ops/ms
Iteration   3: 9.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.667 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (9.628, 9.667, 9.730), stdev = 0.055
  CI (99.9%): [8.667, 10.667] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.391 ops/ms
# Warmup Iteration   2: 9.573 ops/ms
# Warmup Iteration   3: 9.975 ops/ms
Iteration   1: 10.360 ops/ms
Iteration   2: 10.292 ops/ms
Iteration   3: 10.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.354 ±(99.9%) 1.085 ops/ms [Average]
  (min, avg, max) = (10.292, 10.354, 10.411), stdev = 0.059
  CI (99.9%): [9.269, 11.440] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.284 ops/ms
# Warmup Iteration   2: 8.448 ops/ms
# Warmup Iteration   3: 9.401 ops/ms
Iteration   1: 10.097 ops/ms
Iteration   2: 9.947 ops/ms
Iteration   3: 9.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.831 ±(99.9%) 6.186 ops/ms [Average]
  (min, avg, max) = (9.449, 9.831, 10.097), stdev = 0.339
  CI (99.9%): [3.645, 16.016] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.571 ops/ms
# Warmup Iteration   2: 7.898 ops/ms
# Warmup Iteration   3: 8.589 ops/ms
Iteration   1: 8.566 ops/ms
Iteration   2: 8.343 ops/ms
Iteration   3: 8.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.533 ±(99.9%) 3.218 ops/ms [Average]
  (min, avg, max) = (8.343, 8.533, 8.692), stdev = 0.176
  CI (99.9%): [5.316, 11.751] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.624 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.004 ms/op
Iteration   1: 3.182 ±(99.9%) 0.004 ms/op
Iteration   2: 3.187 ±(99.9%) 0.005 ms/op
Iteration   3: 3.089 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.153 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (3.089, 3.153, 3.187), stdev = 0.055
  CI (99.9%): [2.145, 4.161] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.923 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.004 ms/op
Iteration   2: 3.230 ±(99.9%) 0.005 ms/op
Iteration   3: 3.066 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.109 ±(99.9%) 1.932 ms/op [Average]
  (min, avg, max) = (3.031, 3.109, 3.230), stdev = 0.106
  CI (99.9%): [1.177, 5.041] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.871 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.006 ms/op
Iteration   1: 3.219 ±(99.9%) 0.006 ms/op
Iteration   2: 3.321 ±(99.9%) 0.005 ms/op
Iteration   3: 3.056 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.199 ±(99.9%) 2.432 ms/op [Average]
  (min, avg, max) = (3.056, 3.199, 3.321), stdev = 0.133
  CI (99.9%): [0.766, 5.631] (assumes normal distribution)


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
# Warmup Iteration   1: 9.549 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.004 ms/op
Iteration   1: 3.733 ±(99.9%) 0.006 ms/op
Iteration   2: 3.701 ±(99.9%) 0.007 ms/op
Iteration   3: 3.620 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.684 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.620, 3.684, 3.733), stdev = 0.059
  CI (99.9%): [2.617, 4.752] (assumes normal distribution)


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
# Warmup Iteration   1: 7.884 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  10.322 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   2: 3.133 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  17.329 ms/op
                 createUser·p0.9999: 22.661 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.469 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  17.302 ms/op
                 createUser·p0.9999: 20.262 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307688
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23171 
    [ 2.500,  5.000) = 280976 
    [ 5.000,  7.500) = 2837 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.469 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 7.180 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
Iteration   1: 3.215 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.015 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  9.626 ms/op
                 existUser·p0.9999: 21.596 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.214 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  8.716 ms/op
                 existUser·p0.9999: 34.013 ms/op
                 existUser·p1.00:   34.210 ms/op

Iteration   3: 3.229 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.188 ms/op
                 existUser·p0.999:  13.525 ms/op
                 existUser·p0.9999: 26.935 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298065
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26999 
    [ 2.500,  5.000) = 266236 
    [ 5.000,  7.500) = 4135 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     11.939 ms/op
     p(99.9900) =     33.096 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 7.867 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.438 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
Iteration   1: 3.299 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  17.344 ms/op
                 getUser·p0.9999: 26.477 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  10.600 ms/op
                 getUser·p0.9999: 19.857 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  16.120 ms/op
                 getUser·p0.9999: 26.537 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297744
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15963 
    [ 2.500,  5.000) = 274357 
    [ 5.000,  7.500) = 6613 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     16.949 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 7.932 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.012 ms/op
Iteration   1: 3.715 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.324 ms/op
                 listUser·p0.999:  14.204 ms/op
                 listUser·p0.9999: 18.848 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 3.714 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 3.803 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256186
  mean =      3.744 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 249938 
    [ 5.000,  7.500) = 4604 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     20.724 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.667 ± 1.000  ops/ms
ClientPb.existUser                       thrpt       3  10.354 ± 1.085  ops/ms
ClientPb.getUser                         thrpt       3   9.831 ± 6.186  ops/ms
ClientPb.listUser                        thrpt       3   8.533 ± 3.218  ops/ms
ClientPb.createUser                       avgt       3   3.153 ± 1.008   ms/op
ClientPb.existUser                        avgt       3   3.109 ± 1.932   ms/op
ClientPb.getUser                          avgt       3   3.199 ± 2.432   ms/op
ClientPb.listUser                         avgt       3   3.684 ± 1.068   ms/op
ClientPb.createUser                     sample  307688   3.118 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.906           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.186           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.203           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.692           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.084           ms/op
ClientPb.existUser                      sample  298065   3.219 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.939           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.096           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210           ms/op
ClientPb.getUser                        sample  297744   3.224 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.988           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.949           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.444           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  256186   3.744 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.644           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.451           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.562           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.561           ms/op
