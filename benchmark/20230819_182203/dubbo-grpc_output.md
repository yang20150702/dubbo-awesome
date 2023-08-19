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
# Warmup Iteration   1: 4.391 ops/ms
# Warmup Iteration   2: 8.865 ops/ms
# Warmup Iteration   3: 9.647 ops/ms
Iteration   1: 10.166 ops/ms
Iteration   2: 10.041 ops/ms
Iteration   3: 10.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.163 ±(99.9%) 2.194 ops/ms [Average]
  (min, avg, max) = (10.041, 10.163, 10.282), stdev = 0.120
  CI (99.9%): [7.968, 12.357] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.114 ops/ms
# Warmup Iteration   2: 10.343 ops/ms
# Warmup Iteration   3: 10.929 ops/ms
Iteration   1: 10.735 ops/ms
Iteration   2: 10.983 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.786 ±(99.9%) 3.228 ops/ms [Average]
  (min, avg, max) = (10.640, 10.786, 10.983), stdev = 0.177
  CI (99.9%): [7.558, 14.014] (assumes normal distribution)


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
# Warmup Iteration   1: 6.682 ops/ms
# Warmup Iteration   2: 9.797 ops/ms
# Warmup Iteration   3: 10.249 ops/ms
Iteration   1: 10.395 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.330 ±(99.9%) 3.440 ops/ms [Average]
  (min, avg, max) = (10.118, 10.330, 10.477), stdev = 0.189
  CI (99.9%): [6.890, 13.770] (assumes normal distribution)


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
# Warmup Iteration   1: 6.639 ops/ms
# Warmup Iteration   2: 7.508 ops/ms
# Warmup Iteration   3: 8.084 ops/ms
Iteration   1: 8.047 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.062 ±(99.9%) 0.951 ops/ms [Average]
  (min, avg, max) = (8.019, 8.062, 8.120), stdev = 0.052
  CI (99.9%): [7.110, 9.013] (assumes normal distribution)


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.004 ms/op
Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
Iteration   3: 3.056 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.071 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (3.056, 3.071, 3.084), stdev = 0.014
  CI (99.9%): [2.810, 3.332] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 2.908 ±(99.9%) 0.004 ms/op
Iteration   3: 2.959 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (2.908, 2.946, 2.971), stdev = 0.033
  CI (99.9%): [2.336, 3.555] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.002 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.106 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.078 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.041, 3.078, 3.106), stdev = 0.033
  CI (99.9%): [2.477, 3.678] (assumes normal distribution)


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
# Warmup Iteration   1: 5.215 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.012 ms/op
Iteration   1: 3.895 ±(99.9%) 0.015 ms/op
Iteration   2: 3.944 ±(99.9%) 0.014 ms/op
Iteration   3: 3.880 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.906 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (3.880, 3.906, 3.944), stdev = 0.033
  CI (99.9%): [3.298, 4.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.009 ms/op
Iteration   1: 3.105 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  9.434 ms/op
                 createUser·p0.9999: 13.009 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  8.248 ms/op
                 createUser·p0.9999: 18.716 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 3.104 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  11.862 ms/op
                 createUser·p0.9999: 19.969 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310338
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24812 
    [ 2.500,  5.000) = 281384 
    [ 5.000,  7.500) = 3224 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.371 ms/op
     p(99.9000) =     10.311 ms/op
     p(99.9900) =     19.330 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 3.711 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  8.464 ms/op
                 existUser·p0.9999: 12.250 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   2: 2.920 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.756 ms/op
                 existUser·p0.999:  8.053 ms/op
                 existUser·p0.9999: 23.004 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 2.869 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.860 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 18.935 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326909
  mean =      2.936 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46729 
    [ 2.500,  5.000) = 277268 
    [ 5.000,  7.500) = 2219 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =      8.348 ms/op
     p(99.9900) =     20.166 ms/op
     p(99.9990) =     23.256 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
Iteration   1: 3.149 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  9.077 ms/op
                 getUser·p0.9999: 13.525 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 3.099 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 20.482 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   3: 3.006 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.291 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.206 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 26.979 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311284
  mean =      3.083 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31701 
    [ 2.500,  5.000) = 274722 
    [ 5.000,  7.500) = 3885 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.013 ms/op
Iteration   1: 3.940 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.295 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.580 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 18.277 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 3.912 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   8.199 ms/op
                 listUser·p0.999:  23.992 ms/op
                 listUser·p0.9999: 28.279 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   3: 3.863 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  15.747 ms/op
                 listUser·p0.9999: 19.708 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245755
  mean =      3.905 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6846 
    [ 2.500,  5.000) = 209628 
    [ 5.000,  7.500) = 26417 
    [ 7.500, 10.000) = 1993 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.295 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     26.860 ms/op
     p(99.9990) =     28.854 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.163 ± 2.194  ops/ms
ClientGrpc.existUser                       thrpt       3  10.786 ± 3.228  ops/ms
ClientGrpc.getUser                         thrpt       3  10.330 ± 3.440  ops/ms
ClientGrpc.listUser                        thrpt       3   8.062 ± 0.951  ops/ms
ClientGrpc.createUser                       avgt       3   3.071 ± 0.261   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.609   ms/op
ClientGrpc.getUser                          avgt       3   3.078 ± 0.601   ms/op
ClientGrpc.listUser                         avgt       3   3.906 ± 0.608   ms/op
ClientGrpc.createUser                     sample  310338   3.093 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.722           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.371           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.311           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.330           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.430           ms/op
ClientGrpc.existUser                      sample  326909   2.936 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.501           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.348           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.166           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.396           ms/op
ClientGrpc.getUser                        sample  311284   3.083 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.291           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.096           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.929           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.345           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.197           ms/op
ClientGrpc.listUser                       sample  245755   3.905 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.295           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.692           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.303           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.860           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.869           ms/op
