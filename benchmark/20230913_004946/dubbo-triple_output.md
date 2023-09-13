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
# Warmup Iteration   1: 2.555 ops/ms
# Warmup Iteration   2: 5.757 ops/ms
# Warmup Iteration   3: 8.899 ops/ms
Iteration   1: 9.915 ops/ms
Iteration   2: 10.100 ops/ms
Iteration   3: 9.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.993 ±(99.9%) 1.746 ops/ms [Average]
  (min, avg, max) = (9.915, 9.993, 10.100), stdev = 0.096
  CI (99.9%): [8.247, 11.739] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ops/ms
# Warmup Iteration   2: 8.710 ops/ms
# Warmup Iteration   3: 9.959 ops/ms
Iteration   1: 10.199 ops/ms
Iteration   2: 10.296 ops/ms
Iteration   3: 9.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.122 ±(99.9%) 4.072 ops/ms [Average]
  (min, avg, max) = (9.871, 10.122, 10.296), stdev = 0.223
  CI (99.9%): [6.050, 14.194] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 8.691 ops/ms
# Warmup Iteration   3: 9.691 ops/ms
Iteration   1: 9.814 ops/ms
Iteration   2: 10.263 ops/ms
Iteration   3: 9.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.983 ±(99.9%) 4.459 ops/ms [Average]
  (min, avg, max) = (9.814, 9.983, 10.263), stdev = 0.244
  CI (99.9%): [5.524, 14.442] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ops/ms
# Warmup Iteration   2: 7.568 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 8.520 ops/ms
Iteration   2: 8.516 ops/ms
Iteration   3: 8.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.543 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (8.516, 8.543, 8.593), stdev = 0.043
  CI (99.9%): [7.754, 9.332] (assumes normal distribution)


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
# Warmup Iteration   1: 7.679 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.003 ms/op
Iteration   1: 3.222 ±(99.9%) 0.008 ms/op
Iteration   2: 3.132 ±(99.9%) 0.002 ms/op
Iteration   3: 3.227 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.194 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (3.132, 3.194, 3.227), stdev = 0.054
  CI (99.9%): [2.212, 4.176] (assumes normal distribution)


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
# Warmup Iteration   1: 7.745 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.004 ms/op
Iteration   1: 3.236 ±(99.9%) 0.005 ms/op
Iteration   2: 3.082 ±(99.9%) 0.004 ms/op
Iteration   3: 3.209 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.175 ±(99.9%) 1.500 ms/op [Average]
  (min, avg, max) = (3.082, 3.175, 3.236), stdev = 0.082
  CI (99.9%): [1.675, 4.676] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.594 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.003 ms/op
Iteration   1: 3.232 ±(99.9%) 0.002 ms/op
Iteration   2: 3.269 ±(99.9%) 0.003 ms/op
Iteration   3: 3.204 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.235 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (3.204, 3.235, 3.269), stdev = 0.033
  CI (99.9%): [2.638, 3.832] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.052 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.010 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
Iteration   2: 3.833 ±(99.9%) 0.004 ms/op
Iteration   3: 3.762 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.797 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.762, 3.797, 3.833), stdev = 0.035
  CI (99.9%): [3.154, 4.440] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.975 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.009 ms/op
Iteration   1: 3.236 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.736 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 24.717 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   2: 3.361 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  19.715 ms/op
                 createUser·p0.9999: 22.003 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   3: 3.313 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.748 ms/op
                 createUser·p0.999:  14.220 ms/op
                 createUser·p0.9999: 19.737 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290884
  mean =      3.303 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20536 
    [ 2.500,  5.000) = 261862 
    [ 5.000,  7.500) = 7074 
    [ 7.500, 10.000) = 912 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.365 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.779 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
Iteration   1: 3.250 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  11.664 ms/op
                 existUser·p0.9999: 19.830 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  14.107 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   3: 3.106 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.636 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  14.680 ms/op
                 existUser·p0.9999: 20.372 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304321
  mean =      3.152 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17644 
    [ 2.500,  5.000) = 278874 
    [ 5.000,  7.500) = 6397 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     14.293 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     20.675 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.063 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
Iteration   1: 3.240 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.571 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 21.052 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 3.204 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  19.584 ms/op
                 getUser·p0.9999: 22.186 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.272 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  12.936 ms/op
                 getUser·p0.9999: 23.653 ms/op
                 getUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296492
  mean =      3.238 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21834 
    [ 2.500,  5.000) = 266021 
    [ 5.000,  7.500) = 6837 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     18.170 ms/op
     p(99.9900) =     22.785 ms/op
     p(99.9990) =     24.249 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.152 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.014 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 25.985 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   2: 3.791 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  14.347 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 3.792 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 23.120 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249627
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 238827 
    [ 5.000,  7.500) = 8196 
    [ 7.500, 10.000) = 1613 
    [10.000, 12.500) = 422 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     26.329 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.993 ± 1.746  ops/ms
ClientPb.existUser                       thrpt       3  10.122 ± 4.072  ops/ms
ClientPb.getUser                         thrpt       3   9.983 ± 4.459  ops/ms
ClientPb.listUser                        thrpt       3   8.543 ± 0.789  ops/ms
ClientPb.createUser                       avgt       3   3.194 ± 0.982   ms/op
ClientPb.existUser                        avgt       3   3.175 ± 1.500   ms/op
ClientPb.getUser                          avgt       3   3.235 ± 0.597   ms/op
ClientPb.listUser                         avgt       3   3.797 ± 0.643   ms/op
ClientPb.createUser                     sample  290884   3.303 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.189           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.593           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.526           ms/op
ClientPb.existUser                      sample  304321   3.152 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.478           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.293           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.087           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.168           ms/op
ClientPb.getUser                        sample  296492   3.238 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.949           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.170           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.785           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.347           ms/op
ClientPb.listUser                       sample  249627   3.845 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.138           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.642           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.722           ms/op
