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
# Warmup Iteration   1: 3.082 ops/ms
# Warmup Iteration   2: 7.120 ops/ms
# Warmup Iteration   3: 8.172 ops/ms
Iteration   1: 8.522 ops/ms
Iteration   2: 8.483 ops/ms
Iteration   3: 8.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.606 ±(99.9%) 3.280 ops/ms [Average]
  (min, avg, max) = (8.483, 8.606, 8.812), stdev = 0.180
  CI (99.9%): [5.326, 11.886] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.662 ops/ms
# Warmup Iteration   2: 8.561 ops/ms
# Warmup Iteration   3: 8.999 ops/ms
Iteration   1: 8.875 ops/ms
Iteration   2: 9.405 ops/ms
Iteration   3: 9.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.110 ±(99.9%) 4.920 ops/ms [Average]
  (min, avg, max) = (8.875, 9.110, 9.405), stdev = 0.270
  CI (99.9%): [4.191, 14.030] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.151 ops/ms
# Warmup Iteration   2: 8.182 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 8.545 ops/ms
Iteration   2: 8.562 ops/ms
Iteration   3: 7.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.210 ±(99.9%) 10.851 ops/ms [Average]
  (min, avg, max) = (7.523, 8.210, 8.562), stdev = 0.595
  CI (99.9%): [≈ 0, 19.061] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.578 ops/ms
# Warmup Iteration   2: 4.037 ops/ms
# Warmup Iteration   3: 4.553 ops/ms
Iteration   1: 4.628 ops/ms
Iteration   2: 6.556 ops/ms
Iteration   3: 6.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.915 ±(99.9%) 20.328 ops/ms [Average]
  (min, avg, max) = (4.628, 5.915, 6.560), stdev = 1.114
  CI (99.9%): [≈ 0, 26.243] (assumes normal distribution)


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
# Warmup Iteration   1: 5.699 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.006 ms/op
Iteration   1: 3.652 ±(99.9%) 0.004 ms/op
Iteration   2: 3.724 ±(99.9%) 0.004 ms/op
Iteration   3: 3.742 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.706 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.652, 3.706, 3.742), stdev = 0.048
  CI (99.9%): [2.832, 4.581] (assumes normal distribution)


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
# Warmup Iteration   1: 5.082 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.004 ms/op
Iteration   1: 3.467 ±(99.9%) 0.003 ms/op
Iteration   2: 3.596 ±(99.9%) 0.003 ms/op
Iteration   3: 3.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.532 ±(99.9%) 1.177 ms/op [Average]
  (min, avg, max) = (3.467, 3.532, 3.596), stdev = 0.064
  CI (99.9%): [2.355, 4.709] (assumes normal distribution)


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
# Warmup Iteration   1: 5.416 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.005 ms/op
Iteration   1: 3.823 ±(99.9%) 0.005 ms/op
Iteration   2: 3.759 ±(99.9%) 0.004 ms/op
Iteration   3: 3.737 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.773 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.737, 3.773, 3.823), stdev = 0.045
  CI (99.9%): [2.957, 4.588] (assumes normal distribution)


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
# Warmup Iteration   1: 6.908 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.056 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.832 ±(99.9%) 0.026 ms/op
Iteration   1: 4.815 ±(99.9%) 0.019 ms/op
Iteration   2: 4.847 ±(99.9%) 0.015 ms/op
Iteration   3: 4.626 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.763 ±(99.9%) 2.179 ms/op [Average]
  (min, avg, max) = (4.626, 4.763, 4.847), stdev = 0.119
  CI (99.9%): [2.584, 6.942] (assumes normal distribution)


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
# Warmup Iteration   1: 5.484 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.010 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.031 ms/op
                 createUser·p0.999:  12.138 ms/op
                 createUser·p0.9999: 15.305 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   2: 3.677 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  11.972 ms/op
                 createUser·p0.9999: 16.244 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   3: 3.765 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  16.868 ms/op
                 createUser·p0.9999: 20.310 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254381
  mean =      3.776 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5519 
    [ 2.500,  5.000) = 239296 
    [ 5.000,  7.500) = 8351 
    [ 7.500, 10.000) = 697 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     19.352 ms/op
     p(99.9990) =     28.881 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 5.309 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.009 ms/op
Iteration   1: 3.530 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  12.367 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   2: 3.651 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.941 ms/op
                 existUser·p0.9999: 27.041 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.558 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.081 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  8.217 ms/op
                 existUser·p0.9999: 33.194 ms/op
                 existUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268347
  mean =      3.579 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7318 
    [ 2.500,  5.000) = 255357 
    [ 5.000,  7.500) = 4601 
    [ 7.500, 10.000) = 736 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     31.271 ms/op
     p(99.9990) =     33.247 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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
# Warmup Iteration   1: 5.335 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
Iteration   1: 3.801 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  8.469 ms/op
                 getUser·p0.9999: 15.017 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 3.728 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   5.622 ms/op
                 getUser·p0.999:  8.769 ms/op
                 getUser·p0.9999: 16.555 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   3: 3.680 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  7.880 ms/op
                 getUser·p0.9999: 21.030 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256935
  mean =      3.736 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7255 
    [ 2.500,  5.000) = 241670 
    [ 5.000,  7.500) = 7394 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     21.243 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 6.364 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.058 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.851 ±(99.9%) 0.019 ms/op
Iteration   1: 4.820 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.316 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  15.912 ms/op
                 listUser·p0.9999: 24.119 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 4.738 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   6.463 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  18.678 ms/op
                 listUser·p0.9999: 22.018 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 4.889 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.479 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  20.594 ms/op
                 listUser·p0.9999: 23.778 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199665
  mean =      4.815 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 957 
    [ 2.500,  5.000) = 138805 
    [ 5.000,  7.500) = 51236 
    [ 7.500, 10.000) = 7589 
    [10.000, 12.500) = 695 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     23.987 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3   8.606 ±  3.280  ops/ms
ClientGrpc.existUser                       thrpt       3   9.110 ±  4.920  ops/ms
ClientGrpc.getUser                         thrpt       3   8.210 ± 10.851  ops/ms
ClientGrpc.listUser                        thrpt       3   5.915 ± 20.328  ops/ms
ClientGrpc.createUser                       avgt       3   3.706 ±  0.875   ms/op
ClientGrpc.existUser                        avgt       3   3.532 ±  1.177   ms/op
ClientGrpc.getUser                          avgt       3   3.773 ±  0.815   ms/op
ClientGrpc.listUser                         avgt       3   4.763 ±  2.179   ms/op
ClientGrpc.createUser                     sample  254381   3.776 ±  0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.639            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.699            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.489            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.841            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.259            ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.747            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.352            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.704            ms/op
ClientGrpc.existUser                      sample  268347   3.579 ±  0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.850            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.514            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.190            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.465            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.972            ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.748            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.271            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.325            ms/op
ClientGrpc.getUser                        sample  256935   3.736 ±  0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.898            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.686            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.481            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.792            ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.759            ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.503            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.416            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.299            ms/op
ClientGrpc.listUser                       sample  199665   4.815 ±  0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.133            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.530            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.463            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.348            ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.077            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.678            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.987            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.854            ms/op
