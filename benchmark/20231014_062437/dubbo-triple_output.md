# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.107 ops/ms
# Warmup Iteration   2: 2.469 ops/ms
# Warmup Iteration   3: 5.367 ops/ms
Iteration   1: 5.670 ops/ms
Iteration   2: 5.831 ops/ms
Iteration   3: 5.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.766 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (5.670, 5.766, 5.831), stdev = 0.085
  CI (99.9%): [4.221, 7.312] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.660 ops/ms
# Warmup Iteration   2: 4.892 ops/ms
# Warmup Iteration   3: 5.849 ops/ms
Iteration   1: 6.007 ops/ms
Iteration   2: 5.953 ops/ms
Iteration   3: 6.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.077 ±(99.9%) 3.113 ops/ms [Average]
  (min, avg, max) = (5.953, 6.077, 6.272), stdev = 0.171
  CI (99.9%): [2.964, 9.190] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.584 ops/ms
# Warmup Iteration   2: 4.676 ops/ms
# Warmup Iteration   3: 5.498 ops/ms
Iteration   1: 5.474 ops/ms
Iteration   2: 5.611 ops/ms
Iteration   3: 5.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.553 ±(99.9%) 1.284 ops/ms [Average]
  (min, avg, max) = (5.474, 5.553, 5.611), stdev = 0.070
  CI (99.9%): [4.268, 6.837] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.505 ops/ms
# Warmup Iteration   2: 4.245 ops/ms
# Warmup Iteration   3: 5.030 ops/ms
Iteration   1: 5.051 ops/ms
Iteration   2: 5.255 ops/ms
Iteration   3: 4.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.095 ±(99.9%) 2.610 ops/ms [Average]
  (min, avg, max) = (4.980, 5.095, 5.255), stdev = 0.143
  CI (99.9%): [2.485, 7.705] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 17.797 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.600 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.626 ±(99.9%) 0.010 ms/op
Iteration   1: 5.408 ±(99.9%) 0.008 ms/op
Iteration   2: 5.437 ±(99.9%) 0.014 ms/op
Iteration   3: 5.389 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.411 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (5.389, 5.411, 5.437), stdev = 0.024
  CI (99.9%): [4.969, 5.854] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.973 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.771 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.009 ms/op
Iteration   1: 5.201 ±(99.9%) 0.005 ms/op
Iteration   2: 5.253 ±(99.9%) 0.008 ms/op
Iteration   3: 5.333 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.262 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (5.201, 5.262, 5.333), stdev = 0.067
  CI (99.9%): [4.044, 6.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.355 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.251 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.377 ±(99.9%) 0.009 ms/op
Iteration   1: 5.671 ±(99.9%) 0.009 ms/op
Iteration   2: 5.459 ±(99.9%) 0.008 ms/op
Iteration   3: 5.544 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.558 ±(99.9%) 1.949 ms/op [Average]
  (min, avg, max) = (5.459, 5.558, 5.671), stdev = 0.107
  CI (99.9%): [3.609, 7.507] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.120 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.557 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.400 ±(99.9%) 0.014 ms/op
Iteration   1: 6.184 ±(99.9%) 0.012 ms/op
Iteration   2: 6.255 ±(99.9%) 0.015 ms/op
Iteration   3: 6.357 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.265 ±(99.9%) 1.587 ms/op [Average]
  (min, avg, max) = (6.184, 6.265, 6.357), stdev = 0.087
  CI (99.9%): [4.678, 7.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 16.837 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.842 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.748 ±(99.9%) 0.024 ms/op
Iteration   1: 5.599 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   7.258 ms/op
                 createUser·p0.95:   8.110 ms/op
                 createUser·p0.99:   10.992 ms/op
                 createUser·p0.999:  26.072 ms/op
                 createUser·p0.9999: 64.264 ms/op
                 createUser·p1.00:   65.339 ms/op

Iteration   2: 5.446 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.236 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.954 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  24.379 ms/op
                 createUser·p0.9999: 33.719 ms/op
                 createUser·p1.00:   34.734 ms/op

Iteration   3: 5.370 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.347 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  26.592 ms/op
                 createUser·p0.9999: 30.551 ms/op
                 createUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175323
  mean =      5.470 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 73938 
    [ 5.000, 10.000) = 99207 
    [10.000, 15.000) = 1735 
    [15.000, 20.000) = 204 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 105 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 12 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.150 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     25.079 ms/op
     p(99.9900) =     60.127 ms/op
     p(99.9990) =     65.043 ms/op
     p(99.9999) =     65.339 ms/op
    p(100.0000) =     65.339 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.494 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 5.968 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.406 ±(99.9%) 0.020 ms/op
Iteration   1: 5.431 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.281 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   7.283 ms/op
                 existUser·p0.95:   8.471 ms/op
                 existUser·p0.99:   10.961 ms/op
                 existUser·p0.999:  24.580 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 5.133 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.201 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  25.559 ms/op
                 existUser·p0.9999: 29.436 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 5.300 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.291 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  17.161 ms/op
                 existUser·p0.9999: 31.161 ms/op
                 existUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181432
  mean =      5.285 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 94749 
    [ 5.000,  7.500) = 76384 
    [ 7.500, 10.000) = 8042 
    [10.000, 12.500) = 1366 
    [12.500, 15.000) = 374 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.398 ms/op
     p(99.9000) =     23.368 ms/op
     p(99.9900) =     29.444 ms/op
     p(99.9990) =     32.426 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.077 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 6.304 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.752 ±(99.9%) 0.022 ms/op
Iteration   1: 5.563 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.742 ms/op
                 getUser·p0.95:   8.086 ms/op
                 getUser·p0.99:   11.573 ms/op
                 getUser·p0.999:  22.657 ms/op
                 getUser·p0.9999: 29.270 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   2: 5.449 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.294 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.496 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   11.682 ms/op
                 getUser·p0.999:  22.872 ms/op
                 getUser·p0.9999: 27.070 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 5.400 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.609 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.332 ms/op
                 getUser·p0.95:   7.307 ms/op
                 getUser·p0.99:   11.682 ms/op
                 getUser·p0.999:  29.078 ms/op
                 getUser·p0.9999: 37.037 ms/op
                 getUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175603
  mean =      5.469 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 71855 
    [ 5.000,  7.500) = 94057 
    [ 7.500, 10.000) = 6466 
    [10.000, 12.500) = 1830 
    [12.500, 15.000) = 746 
    [15.000, 17.500) = 258 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     34.915 ms/op
     p(99.9990) =     38.566 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.754 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 7.272 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.516 ±(99.9%) 0.025 ms/op
Iteration   1: 6.338 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   12.822 ms/op
                 listUser·p0.999:  25.123 ms/op
                 listUser·p0.9999: 33.942 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 6.304 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.757 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  26.299 ms/op
                 listUser·p0.9999: 32.295 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   3: 6.322 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.747 ms/op
                 listUser·p0.999:  20.709 ms/op
                 listUser·p0.9999: 24.983 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151741
  mean =      6.321 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 10337 
    [ 5.000,  7.500) = 125046 
    [ 7.500, 10.000) = 11353 
    [10.000, 12.500) = 3566 
    [12.500, 15.000) = 708 
    [15.000, 17.500) = 298 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      7.594 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.321 ms/op
     p(99.9000) =     24.167 ms/op
     p(99.9900) =     32.836 ms/op
     p(99.9990) =     34.142 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.766 ± 1.546  ops/ms
ClientPb.existUser                       thrpt       3   6.077 ± 3.113  ops/ms
ClientPb.getUser                         thrpt       3   5.553 ± 1.284  ops/ms
ClientPb.listUser                        thrpt       3   5.095 ± 2.610  ops/ms
ClientPb.createUser                       avgt       3   5.411 ± 0.442   ms/op
ClientPb.existUser                        avgt       3   5.262 ± 1.218   ms/op
ClientPb.getUser                          avgt       3   5.558 ± 1.949   ms/op
ClientPb.listUser                         avgt       3   6.265 ± 1.587   ms/op
ClientPb.createUser                     sample  175323   5.470 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.150           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.938           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.079           ms/op
ClientPb.createUser:createUser·p0.9999  sample          60.127           ms/op
ClientPb.createUser:createUser·p1.00    sample          65.339           ms/op
ClientPb.existUser                      sample  181432   5.285 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.741           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.398           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.368           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.444           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.506           ms/op
ClientPb.getUser                        sample  175603   5.469 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.620           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.733           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.649           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.872           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.915           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.863           ms/op
ClientPb.listUser                       sample  151741   6.321 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.118           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.126           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.321           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.167           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.836           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.210           ms/op
