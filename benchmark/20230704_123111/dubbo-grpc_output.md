# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.570 ops/ms
# Warmup Iteration   2: 7.184 ops/ms
# Warmup Iteration   3: 8.695 ops/ms
Iteration   1: 9.225 ops/ms
Iteration   2: 9.325 ops/ms
Iteration   3: 9.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.295 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (9.225, 9.295, 9.335), stdev = 0.061
  CI (99.9%): [8.190, 10.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.389 ops/ms
# Warmup Iteration   2: 9.205 ops/ms
# Warmup Iteration   3: 9.766 ops/ms
Iteration   1: 9.607 ops/ms
Iteration   2: 9.708 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.715 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (9.607, 9.715, 9.831), stdev = 0.112
  CI (99.9%): [7.667, 11.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.811 ops/ms
# Warmup Iteration   2: 8.700 ops/ms
# Warmup Iteration   3: 9.021 ops/ms
Iteration   1: 9.385 ops/ms
Iteration   2: 9.113 ops/ms
Iteration   3: 9.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.269 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (9.113, 9.269, 9.385), stdev = 0.140
  CI (99.9%): [6.715, 11.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.776 ops/ms
# Warmup Iteration   2: 6.716 ops/ms
# Warmup Iteration   3: 6.982 ops/ms
Iteration   1: 7.158 ops/ms
Iteration   2: 7.217 ops/ms
Iteration   3: 7.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.182 ±(99.9%) 0.565 ops/ms [Average]
  (min, avg, max) = (7.158, 7.182, 7.217), stdev = 0.031
  CI (99.9%): [6.617, 7.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.073 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.004 ms/op
Iteration   1: 3.502 ±(99.9%) 0.002 ms/op
Iteration   2: 3.424 ±(99.9%) 0.004 ms/op
Iteration   3: 3.437 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.454 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.424, 3.454, 3.502), stdev = 0.042
  CI (99.9%): [2.695, 4.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.518 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.003 ms/op
Iteration   1: 3.247 ±(99.9%) 0.003 ms/op
Iteration   2: 3.348 ±(99.9%) 0.004 ms/op
Iteration   3: 3.290 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.295 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (3.247, 3.295, 3.348), stdev = 0.051
  CI (99.9%): [2.367, 4.222] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.858 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.004 ms/op
Iteration   1: 3.377 ±(99.9%) 0.005 ms/op
Iteration   2: 3.401 ±(99.9%) 0.002 ms/op
Iteration   3: 3.403 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.393 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.377, 3.393, 3.403), stdev = 0.015
  CI (99.9%): [3.127, 3.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.983 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.739 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.557 ±(99.9%) 0.011 ms/op
Iteration   1: 4.568 ±(99.9%) 0.024 ms/op
Iteration   2: 4.518 ±(99.9%) 0.019 ms/op
Iteration   3: 4.519 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.535 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (4.518, 4.535, 4.568), stdev = 0.029
  CI (99.9%): [4.012, 5.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.268 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.007 ms/op
Iteration   1: 3.411 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  12.163 ms/op
                 createUser·p0.9999: 14.008 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.465 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  9.105 ms/op
                 createUser·p0.9999: 18.015 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.415 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  16.171 ms/op
                 createUser·p0.9999: 19.003 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 279805
  mean =      3.430 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6198 
    [ 2.500,  5.000) = 269656 
    [ 5.000,  7.500) = 3406 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     26.837 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.007 ms/op
Iteration   1: 3.324 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   4.784 ms/op
                 existUser·p0.999:  8.341 ms/op
                 existUser·p0.9999: 14.303 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 3.349 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  12.054 ms/op
                 existUser·p0.9999: 15.324 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   3: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.151 ms/op
                 existUser·p0.9999: 29.798 ms/op
                 existUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 288334
  mean =      3.329 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9333 
    [ 2.500,  5.000) = 276415 
    [ 5.000,  7.500) = 1965 
    [ 7.500, 10.000) = 362 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     28.475 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.899 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.008 ms/op
Iteration   1: 3.480 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  10.178 ms/op
                 getUser·p0.9999: 14.943 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   2: 3.423 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  8.637 ms/op
                 getUser·p0.9999: 15.849 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 31.405 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 278281
  mean =      3.448 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9057 
    [ 2.500,  5.000) = 265452 
    [ 5.000,  7.500) = 3015 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      9.379 ms/op
     p(99.9900) =     30.458 ms/op
     p(99.9990) =     32.021 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.577 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.664 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.431 ±(99.9%) 0.013 ms/op
Iteration   1: 4.504 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  14.215 ms/op
                 listUser·p0.9999: 16.346 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   2: 4.533 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 20.607 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 4.528 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 21.985 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 212340
  mean =      4.521 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 658 
    [ 2.500,  5.000) = 175180 
    [ 5.000,  7.500) = 33132 
    [ 7.500, 10.000) = 2776 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     15.215 ms/op
     p(99.9900) =     20.964 ms/op
     p(99.9990) =     22.180 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.295 ± 1.105  ops/ms
ClientGrpc.existUser                       thrpt       3   9.715 ± 2.049  ops/ms
ClientGrpc.getUser                         thrpt       3   9.269 ± 2.554  ops/ms
ClientGrpc.listUser                        thrpt       3   7.182 ± 0.565  ops/ms
ClientGrpc.createUser                       avgt       3   3.454 ± 0.759   ms/op
ClientGrpc.existUser                        avgt       3   3.295 ± 0.928   ms/op
ClientGrpc.getUser                          avgt       3   3.393 ± 0.266   ms/op
ClientGrpc.listUser                         avgt       3   4.535 ± 0.522   ms/op
ClientGrpc.createUser                     sample  279805   3.430 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.379           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.341           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.699           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.579           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.837           ms/op
ClientGrpc.existUser                      sample  288334   3.329 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.693           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.175           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.475           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.015           ms/op
ClientGrpc.getUser                        sample  278281   3.448 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.733           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.408           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.379           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.458           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.882           ms/op
ClientGrpc.listUser                       sample  212340   4.521 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.840           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.358           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.324           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.215           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.964           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.348           ms/op
