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
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 7.451 ops/ms
# Warmup Iteration   3: 8.932 ops/ms
Iteration   1: 9.299 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.348 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (9.270, 9.348, 9.475), stdev = 0.111
  CI (99.9%): [7.328, 11.368] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.620 ops/ms
# Warmup Iteration   2: 9.163 ops/ms
# Warmup Iteration   3: 9.557 ops/ms
Iteration   1: 9.828 ops/ms
Iteration   2: 9.644 ops/ms
Iteration   3: 10.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.932 ±(99.9%) 6.414 ops/ms [Average]
  (min, avg, max) = (9.644, 9.932, 10.324), stdev = 0.352
  CI (99.9%): [3.518, 16.346] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.168 ops/ms
# Warmup Iteration   2: 8.913 ops/ms
# Warmup Iteration   3: 9.113 ops/ms
Iteration   1: 9.278 ops/ms
Iteration   2: 9.315 ops/ms
Iteration   3: 9.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.318 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (9.278, 9.318, 9.362), stdev = 0.042
  CI (99.9%): [8.550, 10.087] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.812 ops/ms
# Warmup Iteration   2: 6.802 ops/ms
# Warmup Iteration   3: 7.115 ops/ms
Iteration   1: 7.117 ops/ms
Iteration   2: 7.156 ops/ms
Iteration   3: 7.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.151 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (7.117, 7.151, 7.181), stdev = 0.032
  CI (99.9%): [6.568, 7.734] (assumes normal distribution)


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
# Warmup Iteration   1: 4.804 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.007 ms/op
Iteration   1: 3.508 ±(99.9%) 0.004 ms/op
Iteration   2: 3.455 ±(99.9%) 0.003 ms/op
Iteration   3: 3.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.482 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.455, 3.482, 3.508), stdev = 0.027
  CI (99.9%): [2.998, 3.966] (assumes normal distribution)


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
# Warmup Iteration   1: 4.622 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.004 ms/op
Iteration   1: 3.295 ±(99.9%) 0.004 ms/op
Iteration   2: 3.387 ±(99.9%) 0.002 ms/op
Iteration   3: 3.339 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.340 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (3.295, 3.340, 3.387), stdev = 0.046
  CI (99.9%): [2.507, 4.174] (assumes normal distribution)


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
# Warmup Iteration   1: 5.147 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.004 ms/op
Iteration   1: 3.549 ±(99.9%) 0.005 ms/op
Iteration   2: 3.488 ±(99.9%) 0.003 ms/op
Iteration   3: 3.450 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.496 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.450, 3.496, 3.549), stdev = 0.050
  CI (99.9%): [2.580, 4.412] (assumes normal distribution)


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
# Warmup Iteration   1: 5.745 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.869 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.020 ms/op
Iteration   1: 4.500 ±(99.9%) 0.007 ms/op
Iteration   2: 4.547 ±(99.9%) 0.014 ms/op
Iteration   3: 4.583 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.543 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (4.500, 4.543, 4.583), stdev = 0.042
  CI (99.9%): [3.782, 5.305] (assumes normal distribution)


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
# Warmup Iteration   1: 5.190 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.008 ms/op
Iteration   1: 3.536 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.649 ms/op
                 createUser·p0.999:  11.183 ms/op
                 createUser·p0.9999: 14.840 ms/op
                 createUser·p1.00:   16.056 ms/op

Iteration   2: 3.523 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.052 ms/op
                 createUser·p0.999:  11.898 ms/op
                 createUser·p0.9999: 22.411 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 3.547 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  14.139 ms/op
                 createUser·p0.9999: 20.184 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271455
  mean =      3.536 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8414 
    [ 2.500,  5.000) = 257804 
    [ 5.000,  7.500) = 4222 
    [ 7.500, 10.000) = 626 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     11.701 ms/op
     p(99.9900) =     21.536 ms/op
     p(99.9990) =     22.694 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.006 ms/op
Iteration   1: 3.412 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.881 ms/op
                 existUser·p0.999:  7.980 ms/op
                 existUser·p0.9999: 14.182 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 3.345 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.909 ms/op
                 existUser·p0.999:  7.383 ms/op
                 existUser·p0.9999: 15.979 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 3.340 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  9.347 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 285234
  mean =      3.365 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6015 
    [ 2.500,  5.000) = 276833 
    [ 5.000,  7.500) = 2062 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     17.890 ms/op
     p(99.9990) =     20.255 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 5.148 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.007 ms/op
Iteration   1: 3.492 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.449 ms/op
                 getUser·p0.999:  10.453 ms/op
                 getUser·p0.9999: 14.530 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   2: 3.479 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  8.081 ms/op
                 getUser·p0.9999: 14.366 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  9.683 ms/op
                 getUser·p0.9999: 34.714 ms/op
                 getUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 276480
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9467 
    [ 2.500,  5.000) = 263003 
    [ 5.000,  7.500) = 3487 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      9.406 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     34.946 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 5.979 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.021 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.637 ±(99.9%) 0.013 ms/op
Iteration   1: 4.518 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.308 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  15.404 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.484 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  17.062 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 4.534 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  22.544 ms/op
                 listUser·p0.9999: 31.190 ms/op
                 listUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 212749
  mean =      4.512 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 883 
    [ 2.500,  5.000) = 178023 
    [ 5.000,  7.500) = 30728 
    [ 7.500, 10.000) = 2642 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     16.519 ms/op
     p(99.9900) =     29.503 ms/op
     p(99.9990) =     32.058 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.348 ± 2.020  ops/ms
ClientGrpc.existUser                       thrpt       3   9.932 ± 6.414  ops/ms
ClientGrpc.getUser                         thrpt       3   9.318 ± 0.769  ops/ms
ClientGrpc.listUser                        thrpt       3   7.151 ± 0.583  ops/ms
ClientGrpc.createUser                       avgt       3   3.482 ± 0.484   ms/op
ClientGrpc.existUser                        avgt       3   3.340 ± 0.833   ms/op
ClientGrpc.getUser                          avgt       3   3.496 ± 0.916   ms/op
ClientGrpc.listUser                         avgt       3   4.543 ± 0.762   ms/op
ClientGrpc.createUser                     sample  271455   3.536 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.768           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.693           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.701           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.536           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.741           ms/op
ClientGrpc.existUser                      sample  285234   3.365 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.841           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.823           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.890           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.513           ms/op
ClientGrpc.getUser                        sample  276480   3.470 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.030           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.406           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.013           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.062           ms/op
ClientGrpc.listUser                       sample  212749   4.512 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.073           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.358           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.414           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.519           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.503           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.145           ms/op
