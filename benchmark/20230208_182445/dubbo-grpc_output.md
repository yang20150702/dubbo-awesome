# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.897 ops/ms
# Warmup Iteration   2: 6.567 ops/ms
# Warmup Iteration   3: 7.470 ops/ms
Iteration   1: 7.674 ops/ms
Iteration   2: 7.863 ops/ms
Iteration   3: 7.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.766 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (7.674, 7.766, 7.863), stdev = 0.094
  CI (99.9%): [6.044, 9.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.421 ops/ms
# Warmup Iteration   2: 7.779 ops/ms
# Warmup Iteration   3: 8.020 ops/ms
Iteration   1: 8.622 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.469 ±(99.9%) 2.864 ops/ms [Average]
  (min, avg, max) = (8.308, 8.469, 8.622), stdev = 0.157
  CI (99.9%): [5.605, 11.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.269 ops/ms
# Warmup Iteration   2: 7.581 ops/ms
# Warmup Iteration   3: 7.706 ops/ms
Iteration   1: 7.853 ops/ms
Iteration   2: 8.099 ops/ms
Iteration   3: 7.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.877 ±(99.9%) 3.857 ops/ms [Average]
  (min, avg, max) = (7.678, 7.877, 8.099), stdev = 0.211
  CI (99.9%): [4.019, 11.734] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ops/ms
# Warmup Iteration   2: 5.413 ops/ms
# Warmup Iteration   3: 5.702 ops/ms
Iteration   1: 6.107 ops/ms
Iteration   2: 6.029 ops/ms
Iteration   3: 6.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.110 ±(99.9%) 1.523 ops/ms [Average]
  (min, avg, max) = (6.029, 6.110, 6.196), stdev = 0.083
  CI (99.9%): [4.588, 7.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.692 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.002 ms/op
Iteration   1: 3.968 ±(99.9%) 0.002 ms/op
Iteration   2: 3.868 ±(99.9%) 0.002 ms/op
Iteration   3: 4.082 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.973 ±(99.9%) 1.952 ms/op [Average]
  (min, avg, max) = (3.868, 3.973, 4.082), stdev = 0.107
  CI (99.9%): [2.020, 5.925] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.838 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.003 ms/op
Iteration   1: 4.077 ±(99.9%) 0.002 ms/op
Iteration   2: 4.140 ±(99.9%) 0.003 ms/op
Iteration   3: 3.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.067 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (3.985, 4.067, 4.140), stdev = 0.078
  CI (99.9%): [2.646, 5.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.581 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.002 ms/op
Iteration   1: 3.903 ±(99.9%) 0.002 ms/op
Iteration   2: 4.277 ±(99.9%) 0.004 ms/op
Iteration   3: 3.964 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.048 ±(99.9%) 3.662 ms/op [Average]
  (min, avg, max) = (3.903, 4.048, 4.277), stdev = 0.201
  CI (99.9%): [0.386, 7.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.817 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.685 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.256 ±(99.9%) 0.013 ms/op
Iteration   1: 5.158 ±(99.9%) 0.008 ms/op
Iteration   2: 5.279 ±(99.9%) 0.022 ms/op
Iteration   3: 5.044 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.160 ±(99.9%) 2.147 ms/op [Average]
  (min, avg, max) = (5.044, 5.160, 5.279), stdev = 0.118
  CI (99.9%): [3.013, 7.307] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.582 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.012 ms/op
Iteration   1: 4.141 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   7.651 ms/op
                 createUser·p0.999:  12.831 ms/op
                 createUser·p0.9999: 16.374 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.930 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 18.139 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   3: 3.682 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  10.144 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245529
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4459 
    [ 2.500,  5.000) = 216717 
    [ 5.000,  7.500) = 22234 
    [ 7.500, 10.000) = 1645 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     18.332 ms/op
     p(99.9990) =     20.057 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.194 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.012 ms/op
Iteration   1: 3.664 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  11.702 ms/op
                 existUser·p0.9999: 15.390 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   2: 3.752 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 17.890 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   3: 3.643 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 18.783 ms/op
                 existUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260380
  mean =      3.686 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19975 
    [ 2.500,  5.000) = 221312 
    [ 5.000,  7.500) = 17800 
    [ 7.500, 10.000) = 934 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.645 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     21.109 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.833 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.012 ms/op
Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   5.014 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  11.857 ms/op
                 getUser·p0.9999: 14.852 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 3.875 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.379 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  11.853 ms/op
                 getUser·p0.9999: 18.464 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   3: 3.785 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.258 ms/op
                 getUser·p0.99:   6.666 ms/op
                 getUser·p0.999:  9.543 ms/op
                 getUser·p0.9999: 19.417 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248293
  mean =      3.865 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5974 
    [ 2.500,  5.000) = 220082 
    [ 5.000,  7.500) = 20636 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     18.886 ms/op
     p(99.9990) =     19.812 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.517 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.253 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.090 ±(99.9%) 0.018 ms/op
Iteration   1: 4.860 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  17.874 ms/op
                 listUser·p0.9999: 25.863 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 4.830 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  16.233 ms/op
                 listUser·p0.9999: 20.820 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 4.740 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  19.122 ms/op
                 listUser·p0.9999: 22.594 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199448
  mean =      4.810 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1086 
    [ 2.500,  5.000) = 133853 
    [ 5.000,  7.500) = 56501 
    [ 7.500, 10.000) = 6541 
    [10.000, 12.500) = 902 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.234 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     17.436 ms/op
     p(99.9900) =     24.119 ms/op
     p(99.9990) =     26.412 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.766 ± 1.722  ops/ms
ClientGrpc.existUser                       thrpt       3   8.469 ± 2.864  ops/ms
ClientGrpc.getUser                         thrpt       3   7.877 ± 3.857  ops/ms
ClientGrpc.listUser                        thrpt       3   6.110 ± 1.523  ops/ms
ClientGrpc.createUser                       avgt       3   3.973 ± 1.952   ms/op
ClientGrpc.existUser                        avgt       3   4.067 ± 1.422   ms/op
ClientGrpc.getUser                          avgt       3   4.048 ± 3.662   ms/op
ClientGrpc.listUser                         avgt       3   5.160 ± 2.147   ms/op
ClientGrpc.createUser                     sample  245529   3.908 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.963           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.997           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.250           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.452           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.332           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.709           ms/op
ClientGrpc.existUser                      sample  260380   3.686 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.825           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.645           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.797           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.285           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.266           ms/op
ClientGrpc.getUser                        sample  248293   3.865 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.379           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.436           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.886           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.266           ms/op
ClientGrpc.listUser                       sample  199448   4.810 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.071           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.503           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.436           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.119           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
