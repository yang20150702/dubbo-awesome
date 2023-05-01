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
# Warmup Iteration   1: 2.161 ops/ms
# Warmup Iteration   2: 4.999 ops/ms
# Warmup Iteration   3: 6.689 ops/ms
Iteration   1: 7.030 ops/ms
Iteration   2: 7.151 ops/ms
Iteration   3: 7.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.100 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (7.030, 7.100, 7.151), stdev = 0.062
  CI (99.9%): [5.962, 8.238] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.526 ops/ms
# Warmup Iteration   2: 7.027 ops/ms
# Warmup Iteration   3: 7.387 ops/ms
Iteration   1: 7.584 ops/ms
Iteration   2: 7.680 ops/ms
Iteration   3: 7.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.671 ±(99.9%) 1.506 ops/ms [Average]
  (min, avg, max) = (7.584, 7.671, 7.748), stdev = 0.083
  CI (99.9%): [6.164, 9.177] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.330 ops/ms
# Warmup Iteration   2: 6.523 ops/ms
# Warmup Iteration   3: 7.125 ops/ms
Iteration   1: 7.109 ops/ms
Iteration   2: 7.073 ops/ms
Iteration   3: 7.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.132 ±(99.9%) 1.359 ops/ms [Average]
  (min, avg, max) = (7.073, 7.132, 7.216), stdev = 0.074
  CI (99.9%): [5.774, 8.491] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.288 ops/ms
# Warmup Iteration   2: 5.017 ops/ms
# Warmup Iteration   3: 5.548 ops/ms
Iteration   1: 5.588 ops/ms
Iteration   2: 5.733 ops/ms
Iteration   3: 5.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.627 ±(99.9%) 1.699 ops/ms [Average]
  (min, avg, max) = (5.559, 5.627, 5.733), stdev = 0.093
  CI (99.9%): [3.927, 7.326] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.756 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.841 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.009 ms/op
Iteration   1: 4.173 ±(99.9%) 0.003 ms/op
Iteration   2: 4.189 ±(99.9%) 0.003 ms/op
Iteration   3: 4.072 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.145 ±(99.9%) 1.159 ms/op [Average]
  (min, avg, max) = (4.072, 4.145, 4.189), stdev = 0.064
  CI (99.9%): [2.985, 5.304] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.616 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.004 ms/op
Iteration   1: 4.142 ±(99.9%) 0.004 ms/op
Iteration   2: 4.164 ±(99.9%) 0.003 ms/op
Iteration   3: 4.074 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.127 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (4.074, 4.127, 4.164), stdev = 0.047
  CI (99.9%): [3.275, 4.978] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.886 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.379 ±(99.9%) 0.007 ms/op
Iteration   1: 4.442 ±(99.9%) 0.003 ms/op
Iteration   2: 4.490 ±(99.9%) 0.004 ms/op
Iteration   3: 4.360 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.431 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (4.360, 4.431, 4.490), stdev = 0.066
  CI (99.9%): [3.228, 5.633] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.118 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 6.629 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.815 ±(99.9%) 0.008 ms/op
Iteration   1: 5.604 ±(99.9%) 0.008 ms/op
Iteration   2: 5.777 ±(99.9%) 0.013 ms/op
Iteration   3: 5.845 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.742 ±(99.9%) 2.270 ms/op [Average]
  (min, avg, max) = (5.604, 5.742, 5.845), stdev = 0.124
  CI (99.9%): [3.471, 8.012] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.310 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.017 ms/op
Iteration   1: 4.464 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.734 ms/op
                 createUser·p0.999:  13.024 ms/op
                 createUser·p0.9999: 20.906 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 4.403 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   8.176 ms/op
                 createUser·p0.999:  11.846 ms/op
                 createUser·p0.9999: 22.863 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   3: 4.566 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.726 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  14.402 ms/op
                 createUser·p0.9999: 34.275 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214477
  mean =      4.477 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3430 
    [ 2.500,  5.000) = 163340 
    [ 5.000,  7.500) = 44593 
    [ 7.500, 10.000) = 2474 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      8.169 ms/op
     p(99.9000) =     12.919 ms/op
     p(99.9900) =     32.866 ms/op
     p(99.9990) =     34.790 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.424 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.377 ±(99.9%) 0.013 ms/op
Iteration   1: 4.328 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.435 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   7.881 ms/op
                 existUser·p0.999:  13.299 ms/op
                 existUser·p0.9999: 15.693 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   2: 4.311 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   4.178 ms/op
                 existUser·p0.90:   5.308 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.834 ms/op
                 existUser·p0.999:  15.084 ms/op
                 existUser·p0.9999: 19.784 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 4.165 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.431 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.725 ms/op
                 existUser·p0.999:  13.474 ms/op
                 existUser·p0.9999: 18.785 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224854
  mean =      4.267 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6103 
    [ 2.500,  5.000) = 183315 
    [ 5.000,  7.500) = 32731 
    [ 7.500, 10.000) = 2082 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      4.149 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     19.383 ms/op
     p(99.9990) =     21.815 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.869 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.881 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.669 ±(99.9%) 0.015 ms/op
Iteration   1: 4.543 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.210 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  12.111 ms/op
                 getUser·p0.9999: 17.527 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 4.342 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.243 ms/op
                 getUser·p0.95:   5.702 ms/op
                 getUser·p0.99:   7.848 ms/op
                 getUser·p0.999:  12.217 ms/op
                 getUser·p0.9999: 19.494 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   3: 4.482 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  13.746 ms/op
                 getUser·p0.9999: 25.190 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215393
  mean =      4.454 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4234 
    [ 2.500,  5.000) = 165964 
    [ 5.000,  7.500) = 41615 
    [ 7.500, 10.000) = 2835 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     12.691 ms/op
     p(99.9900) =     23.361 ms/op
     p(99.9990) =     25.357 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.287 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.781 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.907 ±(99.9%) 0.023 ms/op
Iteration   1: 5.841 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  19.890 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 5.862 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 21.498 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 6.008 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  23.874 ms/op
                 listUser·p0.9999: 35.844 ms/op
                 listUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 162550
  mean =      5.903 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 38262 
    [ 5.000,  7.500) = 106822 
    [ 7.500, 10.000) = 14163 
    [10.000, 12.500) = 2394 
    [12.500, 15.000) = 377 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.602 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     34.355 ms/op
     p(99.9990) =     37.208 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.100 ± 1.138  ops/ms
ClientGrpc.existUser                       thrpt       3   7.671 ± 1.506  ops/ms
ClientGrpc.getUser                         thrpt       3   7.132 ± 1.359  ops/ms
ClientGrpc.listUser                        thrpt       3   5.627 ± 1.699  ops/ms
ClientGrpc.createUser                       avgt       3   4.145 ± 1.159   ms/op
ClientGrpc.existUser                        avgt       3   4.127 ± 0.851   ms/op
ClientGrpc.getUser                          avgt       3   4.431 ± 1.203   ms/op
ClientGrpc.listUser                         avgt       3   5.742 ± 2.270   ms/op
ClientGrpc.createUser                     sample  214477   4.477 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.695           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.062           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.169           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.919           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.866           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.931           ms/op
ClientGrpc.existUser                      sample  224854   4.267 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.431           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.775           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.823           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.385           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.383           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  215393   4.454 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.043           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.038           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.389           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.691           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.361           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.461           ms/op
ClientGrpc.listUser                       sample  162550   5.903 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.341           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.602           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.059           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.087           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.355           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.290           ms/op
