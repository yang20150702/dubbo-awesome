# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.511 ops/ms
# Warmup Iteration   2: 8.898 ops/ms
# Warmup Iteration   3: 10.162 ops/ms
Iteration   1: 10.951 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.756 ±(99.9%) 3.077 ops/ms [Average]
  (min, avg, max) = (10.649, 10.756, 10.951), stdev = 0.169
  CI (99.9%): [7.679, 13.833] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.224 ops/ms
# Warmup Iteration   2: 10.587 ops/ms
# Warmup Iteration   3: 10.879 ops/ms
Iteration   1: 11.059 ops/ms
Iteration   2: 10.946 ops/ms
Iteration   3: 11.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.012 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (10.946, 11.012, 11.059), stdev = 0.058
  CI (99.9%): [9.946, 12.078] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.274 ops/ms
# Warmup Iteration   2: 10.278 ops/ms
# Warmup Iteration   3: 10.626 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.766 ops/ms
Iteration   3: 10.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.768 ±(99.9%) 3.050 ops/ms [Average]
  (min, avg, max) = (10.602, 10.768, 10.937), stdev = 0.167
  CI (99.9%): [7.718, 13.819] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.864 ops/ms
# Warmup Iteration   2: 8.147 ops/ms
# Warmup Iteration   3: 8.266 ops/ms
Iteration   1: 8.343 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 8.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.311 ±(99.9%) 0.794 ops/ms [Average]
  (min, avg, max) = (8.262, 8.311, 8.343), stdev = 0.044
  CI (99.9%): [7.517, 9.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 3.021 ±(99.9%) 0.002 ms/op
Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.023 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (3.009, 3.023, 3.038), stdev = 0.015
  CI (99.9%): [2.751, 3.294] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.822 ±(99.9%) 0.004 ms/op
Iteration   1: 2.893 ±(99.9%) 0.002 ms/op
Iteration   2: 2.856 ±(99.9%) 0.003 ms/op
Iteration   3: 2.813 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.731 ms/op [Average]
  (min, avg, max) = (2.813, 2.854, 2.893), stdev = 0.040
  CI (99.9%): [2.123, 3.585] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 3.039 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.003 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.987 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (2.961, 2.987, 3.039), stdev = 0.045
  CI (99.9%): [2.169, 3.805] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.011 ms/op
Iteration   1: 3.837 ±(99.9%) 0.029 ms/op
Iteration   2: 3.830 ±(99.9%) 0.020 ms/op
Iteration   3: 3.805 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.824 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.805, 3.824, 3.837), stdev = 0.017
  CI (99.9%): [3.509, 4.139] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 21.973 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.753 ms/op
                 createUser·p0.999:  8.633 ms/op
                 createUser·p0.9999: 13.025 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  12.326 ms/op
                 createUser·p0.9999: 20.032 ms/op
                 createUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317182
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24078 
    [ 2.500,  5.000) = 290884 
    [ 5.000,  7.500) = 1668 
    [ 7.500, 10.000) = 249 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     22.211 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
Iteration   1: 2.843 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.326 ms/op
                 existUser·p0.9999: 11.780 ms/op
                 existUser·p1.00:   11.944 ms/op

Iteration   2: 2.894 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  10.420 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 2.882 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.235 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334109
  mean =      2.873 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48861 
    [ 2.500,  5.000) = 283474 
    [ 5.000,  7.500) = 1252 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.386 ms/op
     p(99.9900) =     19.698 ms/op
     p(99.9990) =     22.588 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 12.440 ms/op
                 getUser·p1.00:   12.681 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.397 ms/op
                 getUser·p0.9999: 12.921 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.957 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.242 ms/op
                 getUser·p0.9999: 24.811 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320788
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28891 
    [ 2.500,  5.000) = 289999 
    [ 5.000,  7.500) = 1577 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.504 ms/op
     p(99.9900) =     23.474 ms/op
     p(99.9990) =     25.028 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.823 ms/op
                 listUser·p0.999:  11.665 ms/op
                 listUser·p0.9999: 17.984 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 3.849 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.640 ms/op
                 listUser·p0.9999: 15.719 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.853 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.942 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247892
  mean =      3.873 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5365 
    [ 2.500,  5.000) = 220774 
    [ 5.000,  7.500) = 20371 
    [ 7.500, 10.000) = 883 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     13.600 ms/op
     p(99.9900) =     21.549 ms/op
     p(99.9990) =     22.677 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.756 ± 3.077  ops/ms
ClientGrpc.existUser                       thrpt       3  11.012 ± 1.066  ops/ms
ClientGrpc.getUser                         thrpt       3  10.768 ± 3.050  ops/ms
ClientGrpc.listUser                        thrpt       3   8.311 ± 0.794  ops/ms
ClientGrpc.createUser                       avgt       3   3.023 ± 0.271   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.731   ms/op
ClientGrpc.getUser                          avgt       3   2.987 ± 0.818   ms/op
ClientGrpc.listUser                         avgt       3   3.824 ± 0.315   ms/op
ClientGrpc.createUser                     sample  317182   3.026 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.645           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.585           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.103           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.643           ms/op
ClientGrpc.existUser                      sample  334109   2.873 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.653           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.386           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.698           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.708           ms/op
ClientGrpc.getUser                        sample  320788   2.992 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.599           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.474           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.133           ms/op
ClientGrpc.listUser                       sample  247892   3.873 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.947           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.600           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.549           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.774           ms/op
