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
# Warmup Iteration   1: 2.078 ops/ms
# Warmup Iteration   2: 5.821 ops/ms
# Warmup Iteration   3: 8.567 ops/ms
Iteration   1: 9.081 ops/ms
Iteration   2: 9.183 ops/ms
Iteration   3: 9.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.206 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (9.081, 9.206, 9.355), stdev = 0.138
  CI (99.9%): [6.682, 11.731] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.995 ops/ms
# Warmup Iteration   2: 8.576 ops/ms
# Warmup Iteration   3: 9.658 ops/ms
Iteration   1: 9.563 ops/ms
Iteration   2: 9.673 ops/ms
Iteration   3: 9.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.559 ±(99.9%) 2.114 ops/ms [Average]
  (min, avg, max) = (9.442, 9.559, 9.673), stdev = 0.116
  CI (99.9%): [7.446, 11.673] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.094 ops/ms
# Warmup Iteration   2: 8.782 ops/ms
# Warmup Iteration   3: 9.109 ops/ms
Iteration   1: 9.479 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.346 ±(99.9%) 3.269 ops/ms [Average]
  (min, avg, max) = (9.142, 9.346, 9.479), stdev = 0.179
  CI (99.9%): [6.077, 12.615] (assumes normal distribution)


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
# Warmup Iteration   1: 2.478 ops/ms
# Warmup Iteration   2: 7.182 ops/ms
# Warmup Iteration   3: 7.553 ops/ms
Iteration   1: 7.813 ops/ms
Iteration   2: 7.946 ops/ms
Iteration   3: 7.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.902 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (7.813, 7.902, 7.948), stdev = 0.078
  CI (99.9%): [6.483, 9.322] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.921 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.004 ms/op
Iteration   1: 3.526 ±(99.9%) 0.006 ms/op
Iteration   2: 3.574 ±(99.9%) 0.007 ms/op
Iteration   3: 3.408 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.503 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (3.408, 3.503, 3.574), stdev = 0.085
  CI (99.9%): [1.946, 5.059] (assumes normal distribution)


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
# Warmup Iteration   1: 8.481 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.005 ms/op
Iteration   1: 3.348 ±(99.9%) 0.004 ms/op
Iteration   2: 3.300 ±(99.9%) 0.003 ms/op
Iteration   3: 3.268 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.305 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (3.268, 3.305, 3.348), stdev = 0.040
  CI (99.9%): [2.576, 4.035] (assumes normal distribution)


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
# Warmup Iteration   1: 8.761 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.003 ms/op
Iteration   1: 3.529 ±(99.9%) 0.003 ms/op
Iteration   2: 3.475 ±(99.9%) 0.004 ms/op
Iteration   3: 3.401 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.469 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (3.401, 3.469, 3.529), stdev = 0.064
  CI (99.9%): [2.296, 4.641] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.710 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.004 ms/op
Iteration   1: 4.126 ±(99.9%) 0.005 ms/op
Iteration   2: 4.100 ±(99.9%) 0.006 ms/op
Iteration   3: 3.991 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.072 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.991, 4.072, 4.126), stdev = 0.072
  CI (99.9%): [2.762, 5.382] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.777 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.010 ms/op
Iteration   1: 3.475 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  19.654 ms/op
                 createUser·p0.9999: 22.891 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 3.511 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  21.892 ms/op
                 createUser·p0.9999: 23.855 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 3.494 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  17.191 ms/op
                 createUser·p0.9999: 24.834 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274419
  mean =      3.493 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4990 
    [ 2.500,  5.000) = 264569 
    [ 5.000,  7.500) = 3554 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     24.121 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 9.203 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
Iteration   1: 3.419 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.139 ms/op
                 existUser·p0.999:  9.133 ms/op
                 existUser·p0.9999: 22.139 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  21.139 ms/op
                 existUser·p0.9999: 24.825 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  18.104 ms/op
                 existUser·p0.9999: 25.680 ms/op
                 existUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284044
  mean =      3.378 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4428 
    [ 2.500,  5.000) = 274295 
    [ 5.000,  7.500) = 4035 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 10.966 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
Iteration   1: 3.602 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  20.258 ms/op
                 getUser·p0.9999: 22.843 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 3.500 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  19.857 ms/op
                 getUser·p0.9999: 25.395 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.433 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  16.905 ms/op
                 getUser·p0.9999: 24.054 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273206
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4632 
    [ 2.500,  5.000) = 261118 
    [ 5.000,  7.500) = 6039 
    [ 7.500, 10.000) = 793 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     17.852 ms/op
     p(99.9900) =     24.271 ms/op
     p(99.9990) =     26.134 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 9.871 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.012 ms/op
Iteration   1: 4.102 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  19.662 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 4.110 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.687 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 4.158 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 15.335 ms/op
                 listUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232657
  mean =      4.123 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 225167 
    [ 5.000,  7.500) = 5586 
    [ 7.500, 10.000) = 1063 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     24.493 ms/op
     p(99.9990) =     25.581 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.206 ± 2.525  ops/ms
ClientPb.existUser                       thrpt       3   9.559 ± 2.114  ops/ms
ClientPb.getUser                         thrpt       3   9.346 ± 3.269  ops/ms
ClientPb.listUser                        thrpt       3   7.902 ± 1.419  ops/ms
ClientPb.createUser                       avgt       3   3.503 ± 1.556   ms/op
ClientPb.existUser                        avgt       3   3.305 ± 0.730   ms/op
ClientPb.getUser                          avgt       3   3.469 ± 1.173   ms/op
ClientPb.listUser                         avgt       3   4.072 ± 1.310   ms/op
ClientPb.createUser                     sample  274419   3.493 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.323           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.465           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.121           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.657           ms/op
ClientPb.existUser                      sample  284044   3.378 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.199           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.739           ms/op
ClientPb.getUser                        sample  273206   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.104           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.852           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.271           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.214           ms/op
ClientPb.listUser                       sample  232657   4.123 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.597           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.493           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.592           ms/op
