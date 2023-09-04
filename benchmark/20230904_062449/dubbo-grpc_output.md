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
# Warmup Iteration   1: 4.015 ops/ms
# Warmup Iteration   2: 9.218 ops/ms
# Warmup Iteration   3: 10.153 ops/ms
Iteration   1: 10.419 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.472 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (10.419, 10.472, 10.528), stdev = 0.054
  CI (99.9%): [9.479, 11.465] (assumes normal distribution)


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
# Warmup Iteration   1: 7.100 ops/ms
# Warmup Iteration   2: 10.535 ops/ms
# Warmup Iteration   3: 11.009 ops/ms
Iteration   1: 11.003 ops/ms
Iteration   2: 11.001 ops/ms
Iteration   3: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.914 ±(99.9%) 2.786 ops/ms [Average]
  (min, avg, max) = (10.737, 10.914, 11.003), stdev = 0.153
  CI (99.9%): [8.128, 13.700] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.393 ops/ms
# Warmup Iteration   2: 10.046 ops/ms
# Warmup Iteration   3: 10.424 ops/ms
Iteration   1: 10.395 ops/ms
Iteration   2: 10.495 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.405 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (10.323, 10.405, 10.495), stdev = 0.086
  CI (99.9%): [8.829, 11.981] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.965 ops/ms
# Warmup Iteration   2: 7.737 ops/ms
# Warmup Iteration   3: 8.002 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 7.990 ops/ms
Iteration   3: 8.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.043 ±(99.9%) 0.847 ops/ms [Average]
  (min, avg, max) = (7.990, 8.043, 8.072), stdev = 0.046
  CI (99.9%): [7.196, 8.890] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.004 ms/op
Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
Iteration   3: 3.093 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.106 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.093, 3.106, 3.126), stdev = 0.018
  CI (99.9%): [2.782, 3.429] (assumes normal distribution)


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.003 ms/op
Iteration   1: 2.865 ±(99.9%) 0.002 ms/op
Iteration   2: 2.889 ±(99.9%) 0.002 ms/op
Iteration   3: 2.925 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (2.865, 2.893, 2.925), stdev = 0.030
  CI (99.9%): [2.346, 3.441] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
Iteration   3: 3.018 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.017 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (3.010, 3.017, 3.023), stdev = 0.006
  CI (99.9%): [2.900, 3.135] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.011 ms/op
Iteration   1: 3.941 ±(99.9%) 0.014 ms/op
Iteration   2: 3.937 ±(99.9%) 0.037 ms/op
Iteration   3: 3.865 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.915 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (3.865, 3.915, 3.941), stdev = 0.043
  CI (99.9%): [3.135, 4.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.127 ms/op
                 createUser·p0.9999: 17.613 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  8.199 ms/op
                 createUser·p0.9999: 18.120 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  9.082 ms/op
                 createUser·p0.9999: 33.882 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316931
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26513 
    [ 2.500,  5.000) = 288188 
    [ 5.000,  7.500) = 1639 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.724 ms/op
     p(99.9000) =      8.406 ms/op
     p(99.9900) =     31.926 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.549 ms/op
                 existUser·p0.9999: 12.286 ms/op
                 existUser·p1.00:   12.632 ms/op

Iteration   2: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.551 ms/op
                 existUser·p0.999:  7.653 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.868 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.198 ms/op
                 existUser·p0.9999: 28.044 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331790
  mean =      2.893 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43675 
    [ 2.500,  5.000) = 286573 
    [ 5.000,  7.500) = 1149 
    [ 7.500, 10.000) = 233 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.800 ms/op
     p(99.9900) =     20.780 ms/op
     p(99.9990) =     28.291 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.012 ms/op
                 getUser·p0.9999: 14.473 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  7.743 ms/op
                 getUser·p0.9999: 14.058 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.086 ms/op
                 getUser·p0.9999: 16.036 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315900
  mean =      3.039 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 619 
    [ 1.250,  2.500) = 22193 
    [ 2.500,  3.750) = 276361 
    [ 3.750,  5.000) = 14864 
    [ 5.000,  6.250) = 876 
    [ 6.250,  7.500) = 509 
    [ 7.500,  8.750) = 282 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      7.979 ms/op
     p(99.9900) =     15.260 ms/op
     p(99.9990) =     18.345 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 5.445 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.278 ms/op
                 listUser·p0.9999: 21.102 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  16.432 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.302 ms/op
                 listUser·p0.9999: 28.508 ms/op
                 listUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241457
  mean =      3.976 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2589 
    [ 2.500,  5.000) = 214896 
    [ 5.000,  7.500) = 22087 
    [ 7.500, 10.000) = 1426 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     27.553 ms/op
     p(99.9990) =     28.893 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.472 ± 0.993  ops/ms
ClientGrpc.existUser                       thrpt       3  10.914 ± 2.786  ops/ms
ClientGrpc.getUser                         thrpt       3  10.405 ± 1.576  ops/ms
ClientGrpc.listUser                        thrpt       3   8.043 ± 0.847  ops/ms
ClientGrpc.createUser                       avgt       3   3.106 ± 0.323   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 0.548   ms/op
ClientGrpc.getUser                          avgt       3   3.017 ± 0.118   ms/op
ClientGrpc.listUser                         avgt       3   3.915 ± 0.780   ms/op
ClientGrpc.createUser                     sample  316931   3.028 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.759           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.724           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.406           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.926           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.472           ms/op
ClientGrpc.existUser                      sample  331790   2.893 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.735           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.800           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.780           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.606           ms/op
ClientGrpc.getUser                        sample  315900   3.039 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.745           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.260           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.448           ms/op
ClientGrpc.listUser                       sample  241457   3.976 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.104           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.553           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.196           ms/op
