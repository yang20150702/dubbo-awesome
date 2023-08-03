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
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 6.415 ops/ms
# Warmup Iteration   3: 7.960 ops/ms
Iteration   1: 8.174 ops/ms
Iteration   2: 8.341 ops/ms
Iteration   3: 8.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.271 ±(99.9%) 1.585 ops/ms [Average]
  (min, avg, max) = (8.174, 8.271, 8.341), stdev = 0.087
  CI (99.9%): [6.687, 9.856] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.637 ops/ms
# Warmup Iteration   2: 8.091 ops/ms
# Warmup Iteration   3: 8.613 ops/ms
Iteration   1: 8.800 ops/ms
Iteration   2: 8.865 ops/ms
Iteration   3: 8.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.790 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (8.706, 8.790, 8.865), stdev = 0.080
  CI (99.9%): [7.330, 10.251] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.234 ops/ms
# Warmup Iteration   2: 7.525 ops/ms
# Warmup Iteration   3: 8.183 ops/ms
Iteration   1: 8.524 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.362 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (8.274, 8.362, 8.524), stdev = 0.140
  CI (99.9%): [5.803, 10.921] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.141 ops/ms
# Warmup Iteration   2: 5.847 ops/ms
# Warmup Iteration   3: 6.259 ops/ms
Iteration   1: 6.198 ops/ms
Iteration   2: 6.346 ops/ms
Iteration   3: 6.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.285 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (6.198, 6.285, 6.346), stdev = 0.077
  CI (99.9%): [4.872, 7.698] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.604 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.004 ms/op
Iteration   1: 3.824 ±(99.9%) 0.004 ms/op
Iteration   2: 3.852 ±(99.9%) 0.004 ms/op
Iteration   3: 3.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.833 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (3.824, 3.833, 3.852), stdev = 0.016
  CI (99.9%): [3.537, 4.130] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.339 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.003 ms/op
Iteration   1: 3.784 ±(99.9%) 0.005 ms/op
Iteration   2: 3.788 ±(99.9%) 0.003 ms/op
Iteration   3: 3.746 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.772 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (3.746, 3.772, 3.788), stdev = 0.023
  CI (99.9%): [3.349, 4.196] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.644 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.004 ms/op
Iteration   1: 3.967 ±(99.9%) 0.004 ms/op
Iteration   2: 3.797 ±(99.9%) 0.003 ms/op
Iteration   3: 3.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.879 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (3.797, 3.879, 3.967), stdev = 0.085
  CI (99.9%): [2.324, 5.435] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.507 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.651 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.152 ±(99.9%) 0.023 ms/op
Iteration   1: 5.086 ±(99.9%) 0.052 ms/op
Iteration   2: 5.087 ±(99.9%) 0.015 ms/op
Iteration   3: 4.964 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.046 ±(99.9%) 1.289 ms/op [Average]
  (min, avg, max) = (4.964, 5.046, 5.087), stdev = 0.071
  CI (99.9%): [3.757, 6.334] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.003 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.010 ms/op
Iteration   1: 3.897 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  10.988 ms/op
                 createUser·p0.9999: 15.849 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   2: 3.811 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  10.488 ms/op
                 createUser·p0.9999: 16.725 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   3: 3.946 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 20.575 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247129
  mean =      3.884 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6280 
    [ 2.500,  5.000) = 227462 
    [ 5.000,  7.500) = 12135 
    [ 7.500, 10.000) = 889 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     10.945 ms/op
     p(99.9900) =     18.557 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.545 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
Iteration   1: 3.783 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  11.305 ms/op
                 existUser·p0.9999: 15.933 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 3.767 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.268 ms/op
                 existUser·p0.999:  13.584 ms/op
                 existUser·p0.9999: 18.639 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 3.730 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  11.846 ms/op
                 existUser·p0.9999: 30.409 ms/op
                 existUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 255323
  mean =      3.760 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10566 
    [ 2.500,  5.000) = 233235 
    [ 5.000,  7.500) = 10219 
    [ 7.500, 10.000) = 767 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.298 ms/op
     p(99.9000) =     11.769 ms/op
     p(99.9900) =     29.539 ms/op
     p(99.9990) =     30.489 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.742 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.009 ms/op
Iteration   1: 3.888 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  10.060 ms/op
                 getUser·p0.9999: 15.393 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   2: 3.846 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.427 ms/op
                 getUser·p0.999:  11.523 ms/op
                 getUser·p0.9999: 14.943 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  10.969 ms/op
                 getUser·p0.9999: 20.011 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247072
  mean =      3.886 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6547 
    [ 2.500,  5.000) = 226454 
    [ 5.000,  7.500) = 12808 
    [ 7.500, 10.000) = 916 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     10.830 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 6.982 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.280 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.050 ±(99.9%) 0.015 ms/op
Iteration   1: 4.983 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  16.748 ms/op
                 listUser·p0.9999: 20.144 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 5.051 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.537 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  16.607 ms/op
                 listUser·p0.9999: 18.994 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 5.023 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  21.070 ms/op
                 listUser·p0.9999: 32.032 ms/op
                 listUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191229
  mean =      5.019 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 467 
    [ 2.500,  5.000) = 119453 
    [ 5.000,  7.500) = 62743 
    [ 7.500, 10.000) = 7545 
    [10.000, 12.500) = 645 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     28.922 ms/op
     p(99.9990) =     32.648 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.271 ± 1.585  ops/ms
ClientGrpc.existUser                       thrpt       3   8.790 ± 1.461  ops/ms
ClientGrpc.getUser                         thrpt       3   8.362 ± 2.559  ops/ms
ClientGrpc.listUser                        thrpt       3   6.285 ± 1.413  ops/ms
ClientGrpc.createUser                       avgt       3   3.833 ± 0.297   ms/op
ClientGrpc.existUser                        avgt       3   3.772 ± 0.424   ms/op
ClientGrpc.getUser                          avgt       3   3.879 ± 1.556   ms/op
ClientGrpc.listUser                         avgt       3   5.046 ± 1.289   ms/op
ClientGrpc.createUser                     sample  247129   3.884 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.900           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.447           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.945           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.557           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  255323   3.760 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.795           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.298           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.769           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.539           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.540           ms/op
ClientGrpc.getUser                        sample  247072   3.886 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.914           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.087           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.521           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.830           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.071           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  191229   5.019 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.856           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.431           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.922           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.768           ms/op
