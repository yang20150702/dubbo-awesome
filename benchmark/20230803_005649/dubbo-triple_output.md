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
# Warmup Iteration   1: 1.009 ops/ms
# Warmup Iteration   2: 2.441 ops/ms
# Warmup Iteration   3: 5.248 ops/ms
Iteration   1: 6.105 ops/ms
Iteration   2: 5.911 ops/ms
Iteration   3: 6.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.065 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (5.911, 6.065, 6.180), stdev = 0.139
  CI (99.9%): [3.536, 8.595] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.321 ops/ms
# Warmup Iteration   2: 4.648 ops/ms
# Warmup Iteration   3: 6.486 ops/ms
Iteration   1: 6.587 ops/ms
Iteration   2: 6.688 ops/ms
Iteration   3: 6.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.722 ±(99.9%) 2.808 ops/ms [Average]
  (min, avg, max) = (6.587, 6.722, 6.890), stdev = 0.154
  CI (99.9%): [3.913, 9.530] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.761 ops/ms
# Warmup Iteration   2: 5.382 ops/ms
# Warmup Iteration   3: 6.297 ops/ms
Iteration   1: 6.316 ops/ms
Iteration   2: 6.306 ops/ms
Iteration   3: 5.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.153 ±(99.9%) 4.981 ops/ms [Average]
  (min, avg, max) = (5.838, 6.153, 6.316), stdev = 0.273
  CI (99.9%): [1.172, 11.134] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.702 ops/ms
# Warmup Iteration   2: 4.550 ops/ms
# Warmup Iteration   3: 5.148 ops/ms
Iteration   1: 5.169 ops/ms
Iteration   2: 5.059 ops/ms
Iteration   3: 4.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.036 ±(99.9%) 2.675 ops/ms [Average]
  (min, avg, max) = (4.879, 5.036, 5.169), stdev = 0.147
  CI (99.9%): [2.361, 7.710] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 19.930 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.451 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.602 ±(99.9%) 0.013 ms/op
Iteration   1: 5.291 ±(99.9%) 0.015 ms/op
Iteration   2: 5.231 ±(99.9%) 0.009 ms/op
Iteration   3: 5.120 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.214 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (5.120, 5.214, 5.291), stdev = 0.087
  CI (99.9%): [3.632, 6.797] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 16.588 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.880 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.243 ±(99.9%) 0.007 ms/op
Iteration   1: 5.282 ±(99.9%) 0.006 ms/op
Iteration   2: 5.007 ±(99.9%) 0.008 ms/op
Iteration   3: 4.957 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.082 ±(99.9%) 3.196 ms/op [Average]
  (min, avg, max) = (4.957, 5.082, 5.282), stdev = 0.175
  CI (99.9%): [1.886, 8.278] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 15.332 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 6.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.147 ±(99.9%) 0.009 ms/op
Iteration   1: 5.136 ±(99.9%) 0.010 ms/op
Iteration   2: 5.455 ±(99.9%) 0.009 ms/op
Iteration   3: 5.356 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.315 ±(99.9%) 2.978 ms/op [Average]
  (min, avg, max) = (5.136, 5.315, 5.455), stdev = 0.163
  CI (99.9%): [2.337, 8.294] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.222 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.555 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.824 ±(99.9%) 0.016 ms/op
Iteration   1: 5.810 ±(99.9%) 0.012 ms/op
Iteration   2: 6.018 ±(99.9%) 0.009 ms/op
Iteration   3: 5.753 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.860 ±(99.9%) 2.543 ms/op [Average]
  (min, avg, max) = (5.753, 5.860, 6.018), stdev = 0.139
  CI (99.9%): [3.318, 8.403] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.128 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 6.142 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.387 ±(99.9%) 0.023 ms/op
Iteration   1: 5.055 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   4.735 ms/op
                 createUser·p0.90:   6.472 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  21.439 ms/op
                 createUser·p0.9999: 29.251 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   2: 4.887 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.183 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.863 ms/op
                 createUser·p0.999:  24.684 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 4.892 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   10.064 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 29.726 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 194184
  mean =      4.943 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 126832 
    [ 5.000,  7.500) = 59061 
    [ 7.500, 10.000) = 6189 
    [10.000, 12.500) = 1304 
    [12.500, 15.000) = 356 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      7.193 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     23.810 ms/op
     p(99.9900) =     29.174 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.282 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.540 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.960 ±(99.9%) 0.020 ms/op
Iteration   1: 4.761 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.114 ms/op
                 existUser·p0.50:   4.497 ms/op
                 existUser·p0.90:   5.890 ms/op
                 existUser·p0.95:   6.867 ms/op
                 existUser·p0.99:   9.576 ms/op
                 existUser·p0.999:  17.024 ms/op
                 existUser·p0.9999: 29.332 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   2: 4.716 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.865 ms/op
                 existUser·p0.95:   6.668 ms/op
                 existUser·p0.99:   8.831 ms/op
                 existUser·p0.999:  14.918 ms/op
                 existUser·p0.9999: 31.588 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 4.668 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.669 ms/op
                 existUser·p0.95:   6.726 ms/op
                 existUser·p0.99:   9.732 ms/op
                 existUser·p0.999:  16.876 ms/op
                 existUser·p0.9999: 32.473 ms/op
                 existUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 203474
  mean =      4.714 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 152679 
    [ 5.000,  7.500) = 44536 
    [ 7.500, 10.000) = 4739 
    [10.000, 12.500) = 912 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.567 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     31.643 ms/op
     p(99.9990) =     33.317 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.911 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 5.438 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.021 ±(99.9%) 0.019 ms/op
Iteration   1: 5.038 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.339 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   8.176 ms/op
                 getUser·p0.99:   11.944 ms/op
                 getUser·p0.999:  24.276 ms/op
                 getUser·p0.9999: 31.213 ms/op
                 getUser·p1.00:   36.897 ms/op

Iteration   2: 4.790 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.310 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.841 ms/op
                 getUser·p0.95:   6.622 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  14.298 ms/op
                 getUser·p0.9999: 30.537 ms/op
                 getUser·p1.00:   31.425 ms/op

Iteration   3: 5.143 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.286 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.619 ms/op
                 getUser·p0.99:   10.247 ms/op
                 getUser·p0.999:  24.150 ms/op
                 getUser·p0.9999: 27.321 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192512
  mean =      4.986 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 126468 
    [ 5.000,  7.500) = 56635 
    [ 7.500, 10.000) = 6953 
    [10.000, 12.500) = 1636 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.286 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      7.458 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     23.167 ms/op
     p(99.9900) =     30.433 ms/op
     p(99.9990) =     36.715 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 15.913 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 6.420 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.021 ms/op
Iteration   1: 5.883 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.781 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   12.370 ms/op
                 listUser·p0.999:  23.715 ms/op
                 listUser·p0.9999: 26.907 ms/op
                 listUser·p1.00:   30.671 ms/op

Iteration   2: 5.832 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.814 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   11.141 ms/op
                 listUser·p0.999:  25.040 ms/op
                 listUser·p0.9999: 37.948 ms/op
                 listUser·p1.00:   38.863 ms/op

Iteration   3: 5.806 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  20.937 ms/op
                 listUser·p0.9999: 32.046 ms/op
                 listUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164156
  mean =      5.840 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 41122 
    [ 5.000,  7.500) = 109433 
    [ 7.500, 10.000) = 10222 
    [10.000, 12.500) = 2321 
    [12.500, 15.000) = 563 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.441 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.234 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     23.293 ms/op
     p(99.9900) =     36.411 ms/op
     p(99.9990) =     38.737 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.065 ± 2.529  ops/ms
ClientPb.existUser                       thrpt       3   6.722 ± 2.808  ops/ms
ClientPb.getUser                         thrpt       3   6.153 ± 4.981  ops/ms
ClientPb.listUser                        thrpt       3   5.036 ± 2.675  ops/ms
ClientPb.createUser                       avgt       3   5.214 ± 1.582   ms/op
ClientPb.existUser                        avgt       3   5.082 ± 3.196   ms/op
ClientPb.getUser                          avgt       3   5.315 ± 2.978   ms/op
ClientPb.listUser                         avgt       3   5.860 ± 2.543   ms/op
ClientPb.createUser                     sample  194184   4.943 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.655           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.193           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.093           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.810           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.174           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.179           ms/op
ClientPb.existUser                      sample  203474   4.714 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.567           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.750           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.421           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.876           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.643           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  192512   4.986 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.286           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.291           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.458           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.551           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.167           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.433           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.897           ms/op
ClientPb.listUser                       sample  164156   5.840 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.441           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.256           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.293           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.411           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.863           ms/op
