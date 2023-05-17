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
# Warmup Iteration   1: 2.273 ops/ms
# Warmup Iteration   2: 5.851 ops/ms
# Warmup Iteration   3: 7.548 ops/ms
Iteration   1: 7.806 ops/ms
Iteration   2: 7.925 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.918 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (7.806, 7.918, 8.024), stdev = 0.109
  CI (99.9%): [5.926, 9.911] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.852 ops/ms
# Warmup Iteration   2: 7.731 ops/ms
# Warmup Iteration   3: 8.301 ops/ms
Iteration   1: 8.768 ops/ms
Iteration   2: 8.041 ops/ms
Iteration   3: 8.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.281 ±(99.9%) 7.693 ops/ms [Average]
  (min, avg, max) = (8.035, 8.281, 8.768), stdev = 0.422
  CI (99.9%): [0.589, 15.974] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.515 ops/ms
# Warmup Iteration   2: 6.805 ops/ms
# Warmup Iteration   3: 7.621 ops/ms
Iteration   1: 7.744 ops/ms
Iteration   2: 7.684 ops/ms
Iteration   3: 7.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.730 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (7.684, 7.730, 7.762), stdev = 0.041
  CI (99.9%): [6.986, 8.474] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ops/ms
# Warmup Iteration   2: 5.422 ops/ms
# Warmup Iteration   3: 5.976 ops/ms
Iteration   1: 5.969 ops/ms
Iteration   2: 5.859 ops/ms
Iteration   3: 6.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.029 ±(99.9%) 3.766 ops/ms [Average]
  (min, avg, max) = (5.859, 6.029, 6.259), stdev = 0.206
  CI (99.9%): [2.263, 9.795] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.117 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.333 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.003 ms/op
Iteration   1: 4.249 ±(99.9%) 0.004 ms/op
Iteration   2: 4.229 ±(99.9%) 0.004 ms/op
Iteration   3: 4.204 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.227 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (4.204, 4.227, 4.249), stdev = 0.023
  CI (99.9%): [3.813, 4.641] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.170 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.003 ms/op
Iteration   1: 3.854 ±(99.9%) 0.005 ms/op
Iteration   2: 3.797 ±(99.9%) 0.003 ms/op
Iteration   3: 3.645 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.766 ±(99.9%) 1.968 ms/op [Average]
  (min, avg, max) = (3.645, 3.766, 3.854), stdev = 0.108
  CI (99.9%): [1.798, 5.733] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.276 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.003 ms/op
Iteration   1: 4.113 ±(99.9%) 0.005 ms/op
Iteration   2: 4.092 ±(99.9%) 0.004 ms/op
Iteration   3: 3.995 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.067 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.995, 4.067, 4.113), stdev = 0.063
  CI (99.9%): [2.914, 5.220] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.921 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.651 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.355 ±(99.9%) 0.018 ms/op
Iteration   1: 5.363 ±(99.9%) 0.014 ms/op
Iteration   2: 5.246 ±(99.9%) 0.017 ms/op
Iteration   3: 5.031 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.213 ±(99.9%) 3.077 ms/op [Average]
  (min, avg, max) = (5.031, 5.213, 5.363), stdev = 0.169
  CI (99.9%): [2.136, 8.290] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.654 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.011 ms/op
Iteration   1: 4.035 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  10.892 ms/op
                 createUser·p0.9999: 15.420 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   2: 4.131 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   7.791 ms/op
                 createUser·p0.999:  13.743 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   3: 4.170 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.972 ms/op
                 createUser·p0.99:   8.241 ms/op
                 createUser·p0.999:  12.386 ms/op
                 createUser·p0.9999: 21.386 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 233405
  mean =      4.111 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6620 
    [ 2.500,  5.000) = 195104 
    [ 5.000,  7.500) = 28851 
    [ 7.500, 10.000) = 2226 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     12.101 ms/op
     p(99.9900) =     20.895 ms/op
     p(99.9990) =     21.769 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.033 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.010 ms/op
Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  11.693 ms/op
                 existUser·p0.9999: 17.437 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   2: 3.793 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   6.163 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 18.210 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   3: 3.784 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  13.926 ms/op
                 existUser·p0.9999: 21.204 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253109
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8125 
    [ 2.500,  5.000) = 230829 
    [ 5.000,  7.500) = 12858 
    [ 7.500, 10.000) = 907 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     11.565 ms/op
     p(99.9900) =     18.682 ms/op
     p(99.9990) =     21.590 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 6.164 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.014 ms/op
Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   7.679 ms/op
                 getUser·p0.999:  12.007 ms/op
                 getUser·p0.9999: 22.231 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 4.094 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  10.889 ms/op
                 getUser·p0.9999: 22.452 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 4.031 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  11.185 ms/op
                 getUser·p0.9999: 34.013 ms/op
                 getUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235976
  mean =      4.065 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6668 
    [ 2.500,  5.000) = 201480 
    [ 5.000,  7.500) = 25319 
    [ 7.500, 10.000) = 2018 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     32.401 ms/op
     p(99.9990) =     34.448 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 7.349 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.524 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.404 ±(99.9%) 0.024 ms/op
Iteration   1: 5.247 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  18.639 ms/op
                 listUser·p0.9999: 23.936 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 5.230 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   7.389 ms/op
                 listUser·p0.95:   8.296 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 21.191 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   3: 5.235 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.107 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  22.109 ms/op
                 listUser·p0.9999: 23.888 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183476
  mean =      5.237 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 708 
    [ 2.500,  5.000) = 100613 
    [ 5.000,  7.500) = 66967 
    [ 7.500, 10.000) = 12363 
    [10.000, 12.500) = 2027 
    [12.500, 15.000) = 363 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.176 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     23.832 ms/op
     p(99.9990) =     27.339 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.918 ± 1.993  ops/ms
ClientGrpc.existUser                       thrpt       3   8.281 ± 7.693  ops/ms
ClientGrpc.getUser                         thrpt       3   7.730 ± 0.744  ops/ms
ClientGrpc.listUser                        thrpt       3   6.029 ± 3.766  ops/ms
ClientGrpc.createUser                       avgt       3   4.227 ± 0.414   ms/op
ClientGrpc.existUser                        avgt       3   3.766 ± 1.968   ms/op
ClientGrpc.getUser                          avgt       3   4.067 ± 1.153   ms/op
ClientGrpc.listUser                         avgt       3   5.213 ± 3.077   ms/op
ClientGrpc.createUser                     sample  233405   4.111 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.893           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.210           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.774           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.101           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.895           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  253109   3.790 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.595           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.071           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.554           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.565           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.682           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.758           ms/op
ClientGrpc.getUser                        sample  235976   4.065 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.845           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.401           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.537           ms/op
ClientGrpc.listUser                       sample  183476   5.237 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.206           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.176           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.813           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.628           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.832           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
