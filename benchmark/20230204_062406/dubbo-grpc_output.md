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
# Warmup Iteration   1: 3.829 ops/ms
# Warmup Iteration   2: 8.609 ops/ms
# Warmup Iteration   3: 9.822 ops/ms
Iteration   1: 10.129 ops/ms
Iteration   2: 9.879 ops/ms
Iteration   3: 10.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.033 ±(99.9%) 2.451 ops/ms [Average]
  (min, avg, max) = (9.879, 10.033, 10.129), stdev = 0.134
  CI (99.9%): [7.582, 12.485] (assumes normal distribution)


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
# Warmup Iteration   1: 7.145 ops/ms
# Warmup Iteration   2: 10.020 ops/ms
# Warmup Iteration   3: 10.551 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.521 ±(99.9%) 1.424 ops/ms [Average]
  (min, avg, max) = (10.434, 10.521, 10.585), stdev = 0.078
  CI (99.9%): [9.097, 11.944] (assumes normal distribution)


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
# Warmup Iteration   1: 6.659 ops/ms
# Warmup Iteration   2: 9.826 ops/ms
# Warmup Iteration   3: 9.888 ops/ms
Iteration   1: 10.104 ops/ms
Iteration   2: 9.938 ops/ms
Iteration   3: 10.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.066 ±(99.9%) 2.072 ops/ms [Average]
  (min, avg, max) = (9.938, 10.066, 10.156), stdev = 0.114
  CI (99.9%): [7.995, 12.138] (assumes normal distribution)


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
# Warmup Iteration   1: 5.312 ops/ms
# Warmup Iteration   2: 7.292 ops/ms
# Warmup Iteration   3: 7.514 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 7.775 ops/ms
Iteration   3: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.784 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (7.731, 7.784, 7.846), stdev = 0.058
  CI (99.9%): [6.729, 8.840] (assumes normal distribution)


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
# Warmup Iteration   1: 4.365 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.004 ms/op
Iteration   1: 3.135 ±(99.9%) 0.002 ms/op
Iteration   2: 3.208 ±(99.9%) 0.002 ms/op
Iteration   3: 3.274 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.205 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (3.135, 3.205, 3.274), stdev = 0.069
  CI (99.9%): [1.938, 4.473] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.002 ms/op
Iteration   1: 3.071 ±(99.9%) 0.003 ms/op
Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.066 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (3.023, 3.066, 3.105), stdev = 0.042
  CI (99.9%): [2.309, 3.824] (assumes normal distribution)


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.003 ms/op
Iteration   1: 3.290 ±(99.9%) 0.002 ms/op
Iteration   2: 3.252 ±(99.9%) 0.004 ms/op
Iteration   3: 3.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.243 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.188, 3.243, 3.290), stdev = 0.052
  CI (99.9%): [2.302, 4.184] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.219 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.017 ms/op
Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
Iteration   3: 4.233 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.129 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (4.063, 4.129, 4.233), stdev = 0.091
  CI (99.9%): [2.464, 5.795] (assumes normal distribution)


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
# Warmup Iteration   1: 4.755 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.007 ms/op
Iteration   1: 3.326 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  8.561 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.220 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  6.981 ms/op
                 createUser·p0.9999: 18.026 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  18.300 ms/op
                 createUser·p0.9999: 24.427 ms/op
                 createUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 291091
  mean =      3.297 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16622 
    [ 2.500,  5.000) = 273230 
    [ 5.000,  7.500) = 855 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.388 ms/op
     p(99.9900) =     23.852 ms/op
     p(99.9990) =     24.710 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 4.412 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
Iteration   1: 3.193 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.222 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  5.267 ms/op
                 existUser·p0.9999: 13.942 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.675 ms/op
                 existUser·p0.9999: 16.044 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.061 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 303627
  mean =      3.163 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1039 
    [ 1.250,  2.500) = 24604 
    [ 2.500,  3.750) = 233273 
    [ 3.750,  5.000) = 43716 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 181 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.417 ms/op
     p(99.9900) =     16.896 ms/op
     p(99.9990) =     17.918 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.792 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.007 ms/op
Iteration   1: 3.261 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  9.059 ms/op
                 getUser·p0.9999: 17.767 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 3.193 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.854 ms/op
                 getUser·p0.9999: 18.514 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   3: 3.287 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.286 ms/op
                 getUser·p0.9999: 36.897 ms/op
                 getUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295529
  mean =      3.246 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13266 
    [ 2.500,  5.000) = 281016 
    [ 5.000,  7.500) = 875 
    [ 7.500, 10.000) = 211 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.311 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     37.031 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 6.110 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.013 ms/op
Iteration   1: 4.229 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  14.111 ms/op
                 listUser·p0.9999: 16.824 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   2: 4.240 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 22.443 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   3: 4.202 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  17.392 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227243
  mean =      4.224 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1325 
    [ 2.500,  5.000) = 195070 
    [ 5.000,  7.500) = 29088 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.263 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     23.617 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.033 ± 2.451  ops/ms
ClientGrpc.existUser                       thrpt       3  10.521 ± 1.424  ops/ms
ClientGrpc.getUser                         thrpt       3  10.066 ± 2.072  ops/ms
ClientGrpc.listUser                        thrpt       3   7.784 ± 1.055  ops/ms
ClientGrpc.createUser                       avgt       3   3.205 ± 1.268   ms/op
ClientGrpc.existUser                        avgt       3   3.066 ± 0.758   ms/op
ClientGrpc.getUser                          avgt       3   3.243 ± 0.941   ms/op
ClientGrpc.listUser                         avgt       3   4.129 ± 1.665   ms/op
ClientGrpc.createUser                     sample  291091   3.297 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.694           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.273           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.388           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.852           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.805           ms/op
ClientGrpc.existUser                      sample  303627   3.163 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.845           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.146           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.417           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.896           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  295529   3.246 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.752           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.219           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.084           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.311           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.931           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.093           ms/op
ClientGrpc.listUser                       sample  227243   4.224 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.947           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.039           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.263           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.318           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.594           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.757           ms/op
