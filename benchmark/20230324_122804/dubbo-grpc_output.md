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
# Warmup Iteration   1: 4.454 ops/ms
# Warmup Iteration   2: 9.140 ops/ms
# Warmup Iteration   3: 10.162 ops/ms
Iteration   1: 10.637 ops/ms
Iteration   2: 10.474 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.531 ±(99.9%) 1.681 ops/ms [Average]
  (min, avg, max) = (10.474, 10.531, 10.637), stdev = 0.092
  CI (99.9%): [8.850, 12.212] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.526 ops/ms
# Warmup Iteration   2: 10.645 ops/ms
# Warmup Iteration   3: 11.278 ops/ms
Iteration   1: 11.496 ops/ms
Iteration   2: 11.243 ops/ms
Iteration   3: 11.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.381 ±(99.9%) 2.334 ops/ms [Average]
  (min, avg, max) = (11.243, 11.381, 11.496), stdev = 0.128
  CI (99.9%): [9.047, 13.714] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.137 ops/ms
# Warmup Iteration   2: 10.130 ops/ms
# Warmup Iteration   3: 10.564 ops/ms
Iteration   1: 10.690 ops/ms
Iteration   2: 10.504 ops/ms
Iteration   3: 10.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.594 ±(99.9%) 1.693 ops/ms [Average]
  (min, avg, max) = (10.504, 10.594, 10.690), stdev = 0.093
  CI (99.9%): [8.901, 12.287] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.567 ops/ms
# Warmup Iteration   2: 7.932 ops/ms
# Warmup Iteration   3: 7.997 ops/ms
Iteration   1: 8.135 ops/ms
Iteration   2: 8.193 ops/ms
Iteration   3: 8.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.167 ±(99.9%) 0.541 ops/ms [Average]
  (min, avg, max) = (8.135, 8.167, 8.193), stdev = 0.030
  CI (99.9%): [7.626, 8.707] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.150 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.002 ms/op
Iteration   1: 3.006 ±(99.9%) 0.003 ms/op
Iteration   2: 3.016 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (3.006, 3.016, 3.026), stdev = 0.010
  CI (99.9%): [2.830, 3.202] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.577 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.838 ±(99.9%) 0.003 ms/op
Iteration   1: 2.881 ±(99.9%) 0.002 ms/op
Iteration   2: 2.821 ±(99.9%) 0.003 ms/op
Iteration   3: 2.854 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.852 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (2.821, 2.852, 2.881), stdev = 0.030
  CI (99.9%): [2.307, 3.397] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 2.984 ±(99.9%) 0.004 ms/op
Iteration   3: 3.017 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.995 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.984, 2.995, 3.017), stdev = 0.019
  CI (99.9%): [2.650, 3.339] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.179 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.015 ms/op
Iteration   1: 4.018 ±(99.9%) 0.008 ms/op
Iteration   2: 3.911 ±(99.9%) 0.019 ms/op
Iteration   3: 3.916 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.948 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (3.911, 3.948, 4.018), stdev = 0.060
  CI (99.9%): [2.852, 5.045] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.251 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.438 ms/op
                 createUser·p0.9999: 15.747 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.079 ms/op
                 createUser·p0.9999: 17.686 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  12.792 ms/op
                 createUser·p0.9999: 30.704 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318885
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31176 
    [ 2.500,  5.000) = 286385 
    [ 5.000,  7.500) = 997 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.587 ms/op
     p(99.9900) =     26.025 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.112 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.559 ms/op
                 existUser·p0.9999: 11.451 ms/op
                 existUser·p1.00:   11.649 ms/op

Iteration   2: 2.766 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.322 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  6.908 ms/op
                 existUser·p0.9999: 20.429 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   3: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  6.411 ms/op
                 existUser·p0.9999: 15.188 ms/op
                 existUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337706
  mean =      2.842 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48538 
    [ 2.500,  5.000) = 288151 
    [ 5.000,  7.500) = 842 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.432 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     15.547 ms/op
     p(99.9990) =     20.619 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.358 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.322 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  10.697 ms/op
                 getUser·p0.9999: 17.577 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.585 ms/op
                 getUser·p0.9999: 16.819 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.168 ms/op
                 getUser·p0.9999: 25.448 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317736
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22964 
    [ 2.500,  5.000) = 293283 
    [ 5.000,  7.500) = 1012 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.317 ms/op
     p(99.9900) =     24.689 ms/op
     p(99.9990) =     26.039 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 4.974 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.011 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   7.041 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 21.229 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.345 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.113 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 4.056 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 22.253 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239402
  mean =      4.010 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3266 
    [ 2.500,  5.000) = 213231 
    [ 5.000,  7.500) = 21344 
    [ 7.500, 10.000) = 1084 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     16.174 ms/op
     p(99.9900) =     21.565 ms/op
     p(99.9990) =     22.814 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.531 ± 1.681  ops/ms
ClientGrpc.existUser                       thrpt       3  11.381 ± 2.334  ops/ms
ClientGrpc.getUser                         thrpt       3  10.594 ± 1.693  ops/ms
ClientGrpc.listUser                        thrpt       3   8.167 ± 0.541  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.186   ms/op
ClientGrpc.existUser                        avgt       3   2.852 ± 0.545   ms/op
ClientGrpc.getUser                          avgt       3   2.995 ± 0.344   ms/op
ClientGrpc.listUser                         avgt       3   3.948 ± 1.097   ms/op
ClientGrpc.createUser                     sample  318885   3.009 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.650           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.587           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.025           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.769           ms/op
ClientGrpc.existUser                      sample  337706   2.842 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.652           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.578           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.547           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.677           ms/op
ClientGrpc.getUser                        sample  317736   3.020 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.322           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.317           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.689           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.149           ms/op
ClientGrpc.listUser                       sample  239402   4.010 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.345           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.174           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.565           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
