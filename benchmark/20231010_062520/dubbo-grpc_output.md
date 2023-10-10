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
# Warmup Iteration   1: 2.964 ops/ms
# Warmup Iteration   2: 6.700 ops/ms
# Warmup Iteration   3: 7.732 ops/ms
Iteration   1: 8.262 ops/ms
Iteration   2: 8.395 ops/ms
Iteration   3: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.267 ±(99.9%) 2.270 ops/ms [Average]
  (min, avg, max) = (8.146, 8.267, 8.395), stdev = 0.124
  CI (99.9%): [5.998, 10.537] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.910 ops/ms
# Warmup Iteration   2: 8.093 ops/ms
# Warmup Iteration   3: 8.674 ops/ms
Iteration   1: 8.659 ops/ms
Iteration   2: 8.842 ops/ms
Iteration   3: 8.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.744 ±(99.9%) 1.686 ops/ms [Average]
  (min, avg, max) = (8.659, 8.744, 8.842), stdev = 0.092
  CI (99.9%): [7.058, 10.431] (assumes normal distribution)


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
# Warmup Iteration   1: 5.396 ops/ms
# Warmup Iteration   2: 7.565 ops/ms
# Warmup Iteration   3: 7.937 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 8.332 ops/ms
Iteration   3: 8.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.218 ±(99.9%) 2.409 ops/ms [Average]
  (min, avg, max) = (8.073, 8.218, 8.332), stdev = 0.132
  CI (99.9%): [5.809, 10.628] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 5.107 ops/ms
# Warmup Iteration   2: 5.501 ops/ms
# Warmup Iteration   3: 6.282 ops/ms
Iteration   1: 6.388 ops/ms
Iteration   2: 6.495 ops/ms
Iteration   3: 6.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.424 ±(99.9%) 1.126 ops/ms [Average]
  (min, avg, max) = (6.388, 6.424, 6.495), stdev = 0.062
  CI (99.9%): [5.298, 7.550] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.699 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.008 ms/op
Iteration   1: 3.975 ±(99.9%) 0.003 ms/op
Iteration   2: 3.857 ±(99.9%) 0.004 ms/op
Iteration   3: 3.788 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.873 ±(99.9%) 1.725 ms/op [Average]
  (min, avg, max) = (3.788, 3.873, 3.975), stdev = 0.095
  CI (99.9%): [2.148, 5.599] (assumes normal distribution)


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
# Warmup Iteration   1: 5.361 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.003 ms/op
Iteration   1: 3.575 ±(99.9%) 0.005 ms/op
Iteration   2: 3.597 ±(99.9%) 0.003 ms/op
Iteration   3: 3.615 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.596 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (3.575, 3.596, 3.615), stdev = 0.020
  CI (99.9%): [3.232, 3.959] (assumes normal distribution)


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
# Warmup Iteration   1: 5.440 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.022 ms/op
Iteration   1: 3.945 ±(99.9%) 0.003 ms/op
Iteration   2: 3.866 ±(99.9%) 0.003 ms/op
Iteration   3: 3.889 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.900 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.866, 3.900, 3.945), stdev = 0.041
  CI (99.9%): [3.160, 4.640] (assumes normal distribution)


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
# Warmup Iteration   1: 6.028 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.279 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.955 ±(99.9%) 0.015 ms/op
Iteration   1: 4.984 ±(99.9%) 0.013 ms/op
Iteration   2: 4.969 ±(99.9%) 0.025 ms/op
Iteration   3: 4.894 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.949 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (4.894, 4.949, 4.984), stdev = 0.048
  CI (99.9%): [4.069, 5.829] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.557 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.012 ms/op
Iteration   1: 3.822 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  12.321 ms/op
                 createUser·p0.9999: 29.499 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   2: 3.866 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 20.584 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 3.794 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  12.217 ms/op
                 createUser·p0.9999: 29.000 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250843
  mean =      3.827 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11130 
    [ 2.500,  5.000) = 223215 
    [ 5.000,  7.500) = 14190 
    [ 7.500, 10.000) = 1733 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     28.964 ms/op
     p(99.9990) =     29.835 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 5.408 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.010 ms/op
Iteration   1: 3.669 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 23.438 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.606 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  11.839 ms/op
                 existUser·p0.9999: 22.381 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  13.875 ms/op
                 existUser·p0.9999: 24.293 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264037
  mean =      3.634 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16154 
    [ 2.500,  5.000) = 236027 
    [ 5.000,  7.500) = 9735 
    [ 7.500, 10.000) = 1605 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.042 ms/op
     p(99.9000) =     13.679 ms/op
     p(99.9900) =     23.187 ms/op
     p(99.9990) =     24.721 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 5.483 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.012 ms/op
Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 15.155 ms/op
                 getUser·p1.00:   15.958 ms/op

Iteration   2: 3.835 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  13.483 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  11.818 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 244326
  mean =      3.929 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7109 
    [ 2.500,  5.000) = 219458 
    [ 5.000,  7.500) = 15228 
    [ 7.500, 10.000) = 1960 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     20.826 ms/op
     p(99.9990) =     21.503 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 7.025 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.215 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.005 ±(99.9%) 0.016 ms/op
Iteration   1: 5.023 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  15.272 ms/op
                 listUser·p0.9999: 19.255 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 4.963 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  17.845 ms/op
                 listUser·p0.9999: 25.075 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   3: 4.937 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.415 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  21.436 ms/op
                 listUser·p0.9999: 26.330 ms/op
                 listUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 193007
  mean =      4.974 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 330 
    [ 2.500,  5.000) = 128993 
    [ 5.000,  7.500) = 54675 
    [ 7.500, 10.000) = 7348 
    [10.000, 12.500) = 1010 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.414 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     24.753 ms/op
     p(99.9990) =     27.141 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.267 ± 2.270  ops/ms
ClientGrpc.existUser                       thrpt       3   8.744 ± 1.686  ops/ms
ClientGrpc.getUser                         thrpt       3   8.218 ± 2.409  ops/ms
ClientGrpc.listUser                        thrpt       3   6.424 ± 1.126  ops/ms
ClientGrpc.createUser                       avgt       3   3.873 ± 1.725   ms/op
ClientGrpc.existUser                        avgt       3   3.596 ± 0.363   ms/op
ClientGrpc.getUser                          avgt       3   3.900 ± 0.740   ms/op
ClientGrpc.listUser                         avgt       3   4.949 ± 0.880   ms/op
ClientGrpc.createUser                     sample  250843   3.827 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.535           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.235           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.348           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.354           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.964           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.081           ms/op
ClientGrpc.existUser                      sample  264037   3.634 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.734           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.042           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.679           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.187           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.133           ms/op
ClientGrpc.getUser                        sample  244326   3.929 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.657           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.284           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.222           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.826           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  193007   4.974 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.415           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.447           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.732           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.753           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.263           ms/op
