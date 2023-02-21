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
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 6.997 ops/ms
# Warmup Iteration   3: 8.025 ops/ms
Iteration   1: 8.269 ops/ms
Iteration   2: 8.517 ops/ms
Iteration   3: 8.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.361 ±(99.9%) 2.473 ops/ms [Average]
  (min, avg, max) = (8.269, 8.361, 8.517), stdev = 0.136
  CI (99.9%): [5.888, 10.834] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.507 ops/ms
# Warmup Iteration   2: 7.928 ops/ms
# Warmup Iteration   3: 8.464 ops/ms
Iteration   1: 8.497 ops/ms
Iteration   2: 8.706 ops/ms
Iteration   3: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.607 ±(99.9%) 1.911 ops/ms [Average]
  (min, avg, max) = (8.497, 8.607, 8.706), stdev = 0.105
  CI (99.9%): [6.696, 10.518] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ops/ms
# Warmup Iteration   2: 7.617 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 7.591 ops/ms
Iteration   2: 7.858 ops/ms
Iteration   3: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.832 ±(99.9%) 4.188 ops/ms [Average]
  (min, avg, max) = (7.591, 7.832, 8.048), stdev = 0.230
  CI (99.9%): [3.644, 12.021] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ops/ms
# Warmup Iteration   2: 5.626 ops/ms
# Warmup Iteration   3: 5.914 ops/ms
Iteration   1: 6.357 ops/ms
Iteration   2: 5.967 ops/ms
Iteration   3: 6.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.172 ±(99.9%) 3.572 ops/ms [Average]
  (min, avg, max) = (5.967, 6.172, 6.357), stdev = 0.196
  CI (99.9%): [2.600, 9.744] (assumes normal distribution)


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
# Warmup Iteration   1: 6.380 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.011 ms/op
Iteration   1: 4.157 ±(99.9%) 0.003 ms/op
Iteration   2: 4.249 ±(99.9%) 0.002 ms/op
Iteration   3: 3.939 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.115 ±(99.9%) 2.903 ms/op [Average]
  (min, avg, max) = (3.939, 4.115, 4.249), stdev = 0.159
  CI (99.9%): [1.212, 7.018] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.757 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.003 ms/op
Iteration   1: 3.870 ±(99.9%) 0.005 ms/op
Iteration   2: 3.778 ±(99.9%) 0.003 ms/op
Iteration   3: 3.859 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.836 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.778, 3.836, 3.870), stdev = 0.050
  CI (99.9%): [2.927, 4.744] (assumes normal distribution)


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
# Warmup Iteration   1: 6.108 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.007 ms/op
Iteration   1: 4.198 ±(99.9%) 0.003 ms/op
Iteration   2: 4.183 ±(99.9%) 0.004 ms/op
Iteration   3: 4.183 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.188 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (4.183, 4.188, 4.198), stdev = 0.009
  CI (99.9%): [4.030, 4.346] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.502 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.396 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.174 ±(99.9%) 0.013 ms/op
Iteration   1: 5.255 ±(99.9%) 0.008 ms/op
Iteration   2: 5.106 ±(99.9%) 0.013 ms/op
Iteration   3: 5.099 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.153 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (5.099, 5.153, 5.255), stdev = 0.088
  CI (99.9%): [3.546, 6.760] (assumes normal distribution)


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
# Warmup Iteration   1: 5.542 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.011 ms/op
Iteration   1: 4.003 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 4.007 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.408 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  13.386 ms/op
                 createUser·p0.9999: 23.135 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.842 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  13.128 ms/op
                 createUser·p0.9999: 24.040 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 243165
  mean =      3.949 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8177 
    [ 2.500,  5.000) = 209421 
    [ 5.000,  7.500) = 23724 
    [ 7.500, 10.000) = 1217 
    [10.000, 12.500) = 373 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     23.376 ms/op
     p(99.9990) =     26.500 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.663 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.009 ms/op
Iteration   1: 3.819 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.667 ms/op
                 existUser·p0.999:  13.063 ms/op
                 existUser·p0.9999: 15.299 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   2: 3.685 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  9.624 ms/op
                 existUser·p0.9999: 30.692 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   3: 3.689 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  10.074 ms/op
                 existUser·p0.9999: 21.572 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 257217
  mean =      3.730 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8784 
    [ 2.500,  5.000) = 233714 
    [ 5.000,  7.500) = 13536 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     10.781 ms/op
     p(99.9900) =     28.798 ms/op
     p(99.9990) =     31.106 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 6.245 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.013 ms/op
Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  9.725 ms/op
                 getUser·p0.9999: 14.975 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 3.922 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  11.483 ms/op
                 getUser·p0.9999: 17.980 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 3.852 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   6.469 ms/op
                 getUser·p0.999:  10.563 ms/op
                 getUser·p0.9999: 17.893 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247875
  mean =      3.873 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 6097 
    [ 2.500,  3.750) = 113718 
    [ 3.750,  5.000) = 106944 
    [ 5.000,  6.250) = 18051 
    [ 6.250,  7.500) = 1733 
    [ 7.500,  8.750) = 674 
    [ 8.750, 10.000) = 290 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     10.357 ms/op
     p(99.9900) =     17.552 ms/op
     p(99.9990) =     18.990 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 7.026 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.309 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.227 ±(99.9%) 0.018 ms/op
Iteration   1: 4.886 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  14.800 ms/op
                 listUser·p0.9999: 20.560 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 4.980 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.266 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  18.245 ms/op
                 listUser·p0.9999: 26.542 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   3: 5.130 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.592 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 23.177 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192109
  mean =      4.997 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 336 
    [ 2.500,  5.000) = 118042 
    [ 5.000,  7.500) = 64755 
    [ 7.500, 10.000) = 7559 
    [10.000, 12.500) = 886 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =      9.534 ms/op
     p(99.9000) =     18.117 ms/op
     p(99.9900) =     25.918 ms/op
     p(99.9990) =     27.072 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.361 ± 2.473  ops/ms
ClientGrpc.existUser                       thrpt       3   8.607 ± 1.911  ops/ms
ClientGrpc.getUser                         thrpt       3   7.832 ± 4.188  ops/ms
ClientGrpc.listUser                        thrpt       3   6.172 ± 3.572  ops/ms
ClientGrpc.createUser                       avgt       3   4.115 ± 2.903   ms/op
ClientGrpc.existUser                        avgt       3   3.836 ± 0.909   ms/op
ClientGrpc.getUser                          avgt       3   4.188 ± 0.158   ms/op
ClientGrpc.listUser                         avgt       3   5.153 ± 1.607   ms/op
ClientGrpc.createUser                     sample  243165   3.949 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.408           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.030           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.390           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.914           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.714           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.376           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  257217   3.730 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.538           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.071           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.316           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.781           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.798           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.261           ms/op
ClientGrpc.getUser                        sample  247875   3.873 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.357           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.552           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.169           ms/op
ClientGrpc.listUser                       sample  192109   4.997 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.192           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.534           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.117           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.918           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.525           ms/op
