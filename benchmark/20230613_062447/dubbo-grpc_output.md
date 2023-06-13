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
# Warmup Iteration   1: 4.334 ops/ms
# Warmup Iteration   2: 9.300 ops/ms
# Warmup Iteration   3: 10.186 ops/ms
Iteration   1: 10.584 ops/ms
Iteration   2: 10.715 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.669 ±(99.9%) 1.346 ops/ms [Average]
  (min, avg, max) = (10.584, 10.669, 10.715), stdev = 0.074
  CI (99.9%): [9.323, 12.016] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.088 ops/ms
# Warmup Iteration   2: 10.970 ops/ms
# Warmup Iteration   3: 11.246 ops/ms
Iteration   1: 11.210 ops/ms
Iteration   2: 11.251 ops/ms
Iteration   3: 11.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.266 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (11.210, 11.266, 11.336), stdev = 0.065
  CI (99.9%): [10.087, 12.444] (assumes normal distribution)


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
# Warmup Iteration   1: 7.785 ops/ms
# Warmup Iteration   2: 10.286 ops/ms
# Warmup Iteration   3: 10.777 ops/ms
Iteration   1: 10.751 ops/ms
Iteration   2: 10.676 ops/ms
Iteration   3: 10.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.742 ±(99.9%) 1.125 ops/ms [Average]
  (min, avg, max) = (10.676, 10.742, 10.799), stdev = 0.062
  CI (99.9%): [9.617, 11.867] (assumes normal distribution)


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
# Warmup Iteration   1: 5.555 ops/ms
# Warmup Iteration   2: 8.002 ops/ms
# Warmup Iteration   3: 8.370 ops/ms
Iteration   1: 8.211 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.241 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (8.211, 8.241, 8.274), stdev = 0.032
  CI (99.9%): [7.662, 8.820] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.003 ms/op
Iteration   1: 3.067 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 2.990 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (2.990, 3.028, 3.067), stdev = 0.038
  CI (99.9%): [2.330, 3.726] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.917 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.003 ms/op
Iteration   1: 2.788 ±(99.9%) 0.003 ms/op
Iteration   2: 2.860 ±(99.9%) 0.003 ms/op
Iteration   3: 2.837 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.829 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (2.788, 2.829, 2.860), stdev = 0.037
  CI (99.9%): [2.157, 3.500] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.004 ms/op
Iteration   1: 2.988 ±(99.9%) 0.003 ms/op
Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.986 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (2.955, 2.986, 3.014), stdev = 0.030
  CI (99.9%): [2.442, 3.529] (assumes normal distribution)


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.021 ms/op
Iteration   1: 3.903 ±(99.9%) 0.020 ms/op
Iteration   2: 3.895 ±(99.9%) 0.014 ms/op
Iteration   3: 3.878 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (3.878, 3.892, 3.903), stdev = 0.013
  CI (99.9%): [3.658, 4.127] (assumes normal distribution)


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
Iteration   1: 2.965 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.239 ms/op
                 createUser·p0.999:  6.898 ms/op
                 createUser·p0.9999: 13.058 ms/op
                 createUser·p1.00:   13.304 ms/op

Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  10.218 ms/op
                 createUser·p0.9999: 15.876 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.354 ms/op
                 createUser·p0.9999: 25.839 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320203
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32922 
    [ 2.500,  5.000) = 285973 
    [ 5.000,  7.500) = 954 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.233 ms/op
     p(99.9900) =     24.252 ms/op
     p(99.9990) =     26.109 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.005 ms/op
Iteration   1: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.934 ms/op
                 existUser·p0.9999: 18.447 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  6.906 ms/op
                 existUser·p0.9999: 14.205 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   3: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 15.576 ms/op
                 existUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332096
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 958 
    [ 1.250,  2.500) = 48342 
    [ 2.500,  3.750) = 274111 
    [ 3.750,  5.000) = 7621 
    [ 5.000,  6.250) = 600 
    [ 6.250,  7.500) = 216 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     16.354 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.436 ms/op
                 getUser·p0.9999: 12.792 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.423 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.568 ms/op
                 getUser·p0.9999: 14.307 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 2.979 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.430 ms/op
                 getUser·p0.9999: 17.572 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321110
  mean =      2.989 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 443 
    [ 1.250,  2.500) = 21400 
    [ 2.500,  3.750) = 286912 
    [ 3.750,  5.000) = 10951 
    [ 5.000,  6.250) = 780 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.469 ms/op
     p(99.9900) =     15.969 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 5.802 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.010 ms/op
Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.181 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 3.890 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  15.178 ms/op
                 listUser·p0.9999: 22.209 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 3.964 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.525 ms/op
                 listUser·p0.9999: 27.165 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243543
  mean =      3.943 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4079 
    [ 2.500,  5.000) = 214674 
    [ 5.000,  7.500) = 23694 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.802 ms/op
     p(99.9900) =     25.253 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.669 ± 1.346  ops/ms
ClientGrpc.existUser                       thrpt       3  11.266 ± 1.179  ops/ms
ClientGrpc.getUser                         thrpt       3  10.742 ± 1.125  ops/ms
ClientGrpc.listUser                        thrpt       3   8.241 ± 0.579  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.698   ms/op
ClientGrpc.existUser                        avgt       3   2.829 ± 0.672   ms/op
ClientGrpc.getUser                          avgt       3   2.986 ± 0.544   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 0.234   ms/op
ClientGrpc.createUser                     sample  320203   2.998 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.756           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.233           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.252           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.214           ms/op
ClientGrpc.existUser                      sample  332096   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.571           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.816           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.354           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  321110   2.989 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.613           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.469           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.969           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.990           ms/op
ClientGrpc.listUser                       sample  243543   3.943 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.802           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.253           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
