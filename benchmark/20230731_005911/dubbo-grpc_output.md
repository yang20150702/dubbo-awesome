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
# Warmup Iteration   1: 2.380 ops/ms
# Warmup Iteration   2: 6.142 ops/ms
# Warmup Iteration   3: 7.293 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 7.721 ops/ms
Iteration   3: 7.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.744 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (7.719, 7.744, 7.791), stdev = 0.041
  CI (99.9%): [6.994, 8.494] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.272 ops/ms
# Warmup Iteration   2: 7.588 ops/ms
# Warmup Iteration   3: 8.219 ops/ms
Iteration   1: 8.597 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.439 ±(99.9%) 2.728 ops/ms [Average]
  (min, avg, max) = (8.299, 8.439, 8.597), stdev = 0.150
  CI (99.9%): [5.710, 11.167] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.556 ops/ms
# Warmup Iteration   2: 7.422 ops/ms
# Warmup Iteration   3: 7.720 ops/ms
Iteration   1: 8.085 ops/ms
Iteration   2: 8.363 ops/ms
Iteration   3: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.245 ±(99.9%) 2.613 ops/ms [Average]
  (min, avg, max) = (8.085, 8.245, 8.363), stdev = 0.143
  CI (99.9%): [5.631, 10.858] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.992 ops/ms
# Warmup Iteration   2: 5.556 ops/ms
# Warmup Iteration   3: 6.155 ops/ms
Iteration   1: 6.219 ops/ms
Iteration   2: 6.201 ops/ms
Iteration   3: 6.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.226 ±(99.9%) 0.526 ops/ms [Average]
  (min, avg, max) = (6.201, 6.226, 6.257), stdev = 0.029
  CI (99.9%): [5.699, 6.752] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.168 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.009 ms/op
Iteration   1: 3.943 ±(99.9%) 0.003 ms/op
Iteration   2: 3.926 ±(99.9%) 0.003 ms/op
Iteration   3: 3.981 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.950 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.926, 3.950, 3.981), stdev = 0.028
  CI (99.9%): [3.441, 4.459] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.868 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.003 ms/op
Iteration   1: 3.740 ±(99.9%) 0.002 ms/op
Iteration   2: 3.780 ±(99.9%) 0.002 ms/op
Iteration   3: 3.880 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.800 ±(99.9%) 1.318 ms/op [Average]
  (min, avg, max) = (3.740, 3.800, 3.880), stdev = 0.072
  CI (99.9%): [2.481, 5.118] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.190 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.890 ±(99.9%) 0.006 ms/op
Iteration   2: 3.849 ±(99.9%) 0.002 ms/op
Iteration   3: 3.819 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.853 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.819, 3.853, 3.890), stdev = 0.036
  CI (99.9%): [3.203, 4.503] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.508 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.112 ±(99.9%) 0.012 ms/op
Iteration   1: 5.110 ±(99.9%) 0.017 ms/op
Iteration   2: 5.095 ±(99.9%) 0.018 ms/op
Iteration   3: 5.216 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.140 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (5.095, 5.140, 5.216), stdev = 0.066
  CI (99.9%): [3.928, 6.353] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.319 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.012 ms/op
Iteration   1: 3.980 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  10.791 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 4.038 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   5.153 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  11.790 ms/op
                 createUser·p0.9999: 27.599 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 3.959 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   7.345 ms/op
                 createUser·p0.999:  13.961 ms/op
                 createUser·p0.9999: 28.797 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240487
  mean =      3.992 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6739 
    [ 2.500,  5.000) = 207296 
    [ 5.000,  7.500) = 24140 
    [ 7.500, 10.000) = 1723 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     29.249 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.913 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.011 ms/op
Iteration   1: 3.823 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  12.259 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 3.746 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  12.981 ms/op
                 existUser·p0.9999: 21.257 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 3.857 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.766 ms/op
                 existUser·p0.999:  13.748 ms/op
                 existUser·p0.9999: 39.882 ms/op
                 existUser·p1.00:   40.370 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 251913
  mean =      3.808 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 232488 
    [ 5.000, 10.000) = 18640 
    [10.000, 15.000) = 629 
    [15.000, 20.000) = 81 
    [20.000, 25.000) = 43 
    [25.000, 30.000) = 21 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     40.205 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.575 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
Iteration   1: 3.882 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.294 ms/op
                 getUser·p0.999:  11.036 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.837 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  12.452 ms/op
                 getUser·p0.9999: 18.328 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 3.874 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.421 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  10.592 ms/op
                 getUser·p0.9999: 19.841 ms/op
                 getUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248233
  mean =      3.864 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8366 
    [ 2.500,  5.000) = 219506 
    [ 5.000,  7.500) = 18086 
    [ 7.500, 10.000) = 1831 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      7.345 ms/op
     p(99.9000) =     11.318 ms/op
     p(99.9900) =     20.684 ms/op
     p(99.9990) =     22.978 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 6.786 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.593 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.195 ±(99.9%) 0.021 ms/op
Iteration   1: 5.101 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  16.895 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 5.204 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   4.882 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   8.036 ms/op
                 listUser·p0.99:   10.600 ms/op
                 listUser·p0.999:  20.007 ms/op
                 listUser·p0.9999: 34.790 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   3: 5.145 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   10.460 ms/op
                 listUser·p0.999:  19.852 ms/op
                 listUser·p0.9999: 27.911 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186282
  mean =      5.149 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 504 
    [ 2.500,  5.000) = 105616 
    [ 5.000,  7.500) = 68501 
    [ 7.500, 10.000) = 9286 
    [10.000, 12.500) = 1665 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     34.958 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.744 ± 0.750  ops/ms
ClientGrpc.existUser                       thrpt       3   8.439 ± 2.728  ops/ms
ClientGrpc.getUser                         thrpt       3   8.245 ± 2.613  ops/ms
ClientGrpc.listUser                        thrpt       3   6.226 ± 0.526  ops/ms
ClientGrpc.createUser                       avgt       3   3.950 ± 0.509   ms/op
ClientGrpc.existUser                        avgt       3   3.800 ± 1.318   ms/op
ClientGrpc.getUser                          avgt       3   3.853 ± 0.650   ms/op
ClientGrpc.listUser                         avgt       3   5.140 ± 1.213   ms/op
ClientGrpc.createUser                     sample  240487   3.992 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.706           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.546           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.447           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.599           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.984           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.262           ms/op
ClientGrpc.existUser                      sample  251913   3.808 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.528           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.825           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.422           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.353           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.722           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          40.370           ms/op
ClientGrpc.getUser                        sample  248233   3.864 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.421           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.333           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.345           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.318           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.684           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.233           ms/op
ClientGrpc.listUser                       sample  186282   5.149 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.837           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.387           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.235           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.426           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.127           ms/op
