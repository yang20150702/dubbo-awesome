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
# Warmup Iteration   1: 4.710 ops/ms
# Warmup Iteration   2: 9.038 ops/ms
# Warmup Iteration   3: 10.221 ops/ms
Iteration   1: 10.369 ops/ms
Iteration   2: 10.523 ops/ms
Iteration   3: 10.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.544 ±(99.9%) 3.416 ops/ms [Average]
  (min, avg, max) = (10.369, 10.544, 10.742), stdev = 0.187
  CI (99.9%): [7.128, 13.961] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.330 ops/ms
# Warmup Iteration   2: 10.628 ops/ms
# Warmup Iteration   3: 10.946 ops/ms
Iteration   1: 10.981 ops/ms
Iteration   2: 11.152 ops/ms
Iteration   3: 11.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.047 ±(99.9%) 1.675 ops/ms [Average]
  (min, avg, max) = (10.981, 11.047, 11.152), stdev = 0.092
  CI (99.9%): [9.373, 12.722] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.712 ops/ms
# Warmup Iteration   2: 10.035 ops/ms
# Warmup Iteration   3: 10.583 ops/ms
Iteration   1: 10.629 ops/ms
Iteration   2: 10.552 ops/ms
Iteration   3: 10.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.589 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (10.552, 10.589, 10.629), stdev = 0.039
  CI (99.9%): [9.882, 11.295] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.370 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 8.221 ops/ms
Iteration   1: 8.373 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.286 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (8.179, 8.286, 8.373), stdev = 0.098
  CI (99.9%): [6.491, 10.081] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.014 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (2.995, 3.014, 3.038), stdev = 0.022
  CI (99.9%): [2.621, 3.408] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.795 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.003 ms/op
Iteration   1: 2.830 ±(99.9%) 0.003 ms/op
Iteration   2: 2.835 ±(99.9%) 0.003 ms/op
Iteration   3: 2.799 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.821 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.799, 2.821, 2.835), stdev = 0.020
  CI (99.9%): [2.460, 3.183] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.017 ms/op
Iteration   1: 3.048 ±(99.9%) 0.004 ms/op
Iteration   2: 3.025 ±(99.9%) 0.001 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.006, 3.026, 3.048), stdev = 0.021
  CI (99.9%): [2.641, 3.411] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.889 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.007 ms/op
Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
Iteration   2: 3.934 ±(99.9%) 0.012 ms/op
Iteration   3: 3.932 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (3.918, 3.928, 3.934), stdev = 0.009
  CI (99.9%): [3.772, 4.084] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.833 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.328 ms/op
                 createUser·p0.9999: 11.730 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.243 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 12.984 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  11.472 ms/op
                 createUser·p0.9999: 23.587 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317786
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26280 
    [ 2.500,  5.000) = 290235 
    [ 5.000,  7.500) = 764 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.243 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     21.864 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.006 ms/op
Iteration   1: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  6.583 ms/op
                 existUser·p0.9999: 11.841 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   2: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  5.493 ms/op
                 existUser·p0.9999: 13.221 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.078 ms/op
                 existUser·p0.9999: 13.399 ms/op
                 existUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332455
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2235 
    [ 1.250,  2.500) = 41429 
    [ 2.500,  3.750) = 278575 
    [ 3.750,  5.000) = 9164 
    [ 5.000,  6.250) = 777 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.038 ms/op
     p(99.9900) =     13.169 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.501 ms/op
                 getUser·p0.9999: 12.081 ms/op
                 getUser·p1.00:   12.354 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.146 ms/op
                 getUser·p0.9999: 13.264 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.899 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.394 ms/op
                 getUser·p0.999:  6.645 ms/op
                 getUser·p0.9999: 14.647 ms/op
                 getUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323551
  mean =      2.965 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2073 
    [ 1.250,  2.500) = 27345 
    [ 2.500,  3.750) = 281126 
    [ 3.750,  5.000) = 11426 
    [ 5.000,  6.250) = 969 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     13.915 ms/op
     p(99.9990) =     14.754 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 5.094 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.010 ms/op
Iteration   1: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  12.683 ms/op
                 listUser·p0.9999: 15.628 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.966 ms/op
                 listUser·p0.999:  14.838 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244878
  mean =      3.922 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4963 
    [ 2.500,  5.000) = 216363 
    [ 5.000,  7.500) = 22119 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.544 ± 3.416  ops/ms
ClientGrpc.existUser                       thrpt       3  11.047 ± 1.675  ops/ms
ClientGrpc.getUser                         thrpt       3  10.589 ± 0.706  ops/ms
ClientGrpc.listUser                        thrpt       3   8.286 ± 1.795  ops/ms
ClientGrpc.createUser                       avgt       3   3.014 ± 0.393   ms/op
ClientGrpc.existUser                        avgt       3   2.821 ± 0.362   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 0.385   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 0.156   ms/op
ClientGrpc.createUser                     sample  317786   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.243           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.978           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.864           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.986           ms/op
ClientGrpc.existUser                      sample  332455   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.038           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.169           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          13.894           ms/op
ClientGrpc.getUser                        sample  323551   2.965 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.568           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.437           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.348           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.915           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.844           ms/op
ClientGrpc.listUser                       sample  244878   3.922 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.957           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.468           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.972           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.987           ms/op
