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
# Warmup Iteration   1: 3.406 ops/ms
# Warmup Iteration   2: 6.689 ops/ms
# Warmup Iteration   3: 8.559 ops/ms
Iteration   1: 8.486 ops/ms
Iteration   2: 8.995 ops/ms
Iteration   3: 8.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.776 ±(99.9%) 4.779 ops/ms [Average]
  (min, avg, max) = (8.486, 8.776, 8.995), stdev = 0.262
  CI (99.9%): [3.998, 13.555] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.419 ops/ms
# Warmup Iteration   2: 8.712 ops/ms
# Warmup Iteration   3: 9.475 ops/ms
Iteration   1: 9.515 ops/ms
Iteration   2: 9.621 ops/ms
Iteration   3: 9.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.565 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (9.515, 9.565, 9.621), stdev = 0.053
  CI (99.9%): [8.596, 10.535] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.823 ops/ms
# Warmup Iteration   2: 8.346 ops/ms
# Warmup Iteration   3: 8.963 ops/ms
Iteration   1: 8.994 ops/ms
Iteration   2: 9.042 ops/ms
Iteration   3: 8.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.003 ±(99.9%) 0.643 ops/ms [Average]
  (min, avg, max) = (8.973, 9.003, 9.042), stdev = 0.035
  CI (99.9%): [8.360, 9.646] (assumes normal distribution)


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
# Warmup Iteration   1: 4.500 ops/ms
# Warmup Iteration   2: 6.448 ops/ms
# Warmup Iteration   3: 6.441 ops/ms
Iteration   1: 6.711 ops/ms
Iteration   2: 6.740 ops/ms
Iteration   3: 6.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.749 ±(99.9%) 0.788 ops/ms [Average]
  (min, avg, max) = (6.711, 6.749, 6.796), stdev = 0.043
  CI (99.9%): [5.961, 7.536] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.299 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.010 ms/op
Iteration   1: 3.626 ±(99.9%) 0.003 ms/op
Iteration   2: 3.522 ±(99.9%) 0.009 ms/op
Iteration   3: 3.450 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.533 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (3.450, 3.533, 3.626), stdev = 0.088
  CI (99.9%): [1.921, 5.144] (assumes normal distribution)


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
# Warmup Iteration   1: 4.876 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.003 ms/op
Iteration   1: 3.499 ±(99.9%) 0.003 ms/op
Iteration   2: 3.380 ±(99.9%) 0.003 ms/op
Iteration   3: 3.234 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.371 ±(99.9%) 2.418 ms/op [Average]
  (min, avg, max) = (3.234, 3.371, 3.499), stdev = 0.133
  CI (99.9%): [0.953, 5.789] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.042 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.005 ms/op
Iteration   1: 3.368 ±(99.9%) 0.004 ms/op
Iteration   2: 3.463 ±(99.9%) 0.004 ms/op
Iteration   3: 3.545 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.459 ±(99.9%) 1.616 ms/op [Average]
  (min, avg, max) = (3.368, 3.459, 3.545), stdev = 0.089
  CI (99.9%): [1.843, 5.076] (assumes normal distribution)


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
# Warmup Iteration   1: 6.821 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.013 ms/op
Iteration   1: 4.659 ±(99.9%) 0.030 ms/op
Iteration   2: 4.705 ±(99.9%) 0.008 ms/op
Iteration   3: 4.604 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.656 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (4.604, 4.656, 4.705), stdev = 0.051
  CI (99.9%): [3.731, 5.581] (assumes normal distribution)


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.010 ms/op
Iteration   1: 3.597 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  11.828 ms/op
                 createUser·p0.9999: 14.682 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   2: 3.510 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  7.455 ms/op
                 createUser·p0.9999: 18.321 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   3: 3.647 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  13.959 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267820
  mean =      3.584 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9866 
    [ 2.500,  5.000) = 250700 
    [ 5.000,  7.500) = 6493 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     12.245 ms/op
     p(99.9900) =     19.373 ms/op
     p(99.9990) =     19.889 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.008 ms/op
Iteration   1: 3.364 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  8.567 ms/op
                 existUser·p0.9999: 14.385 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 3.368 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.550 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 15.286 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   3: 3.373 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  7.692 ms/op
                 existUser·p0.9999: 19.105 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 284949
  mean =      3.369 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 227 
    [ 1.250,  2.500) = 9261 
    [ 2.500,  3.750) = 223143 
    [ 3.750,  5.000) = 48202 
    [ 5.000,  6.250) = 2973 
    [ 6.250,  7.500) = 588 
    [ 7.500,  8.750) = 289 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      8.652 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     19.605 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 5.079 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.009 ms/op
Iteration   1: 3.588 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 15.522 ms/op
                 getUser·p1.00:   15.974 ms/op

Iteration   2: 3.464 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 15.881 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.764 ms/op
                 getUser·p0.999:  8.447 ms/op
                 getUser·p0.9999: 28.869 ms/op
                 getUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 272984
  mean =      3.517 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8714 
    [ 2.500,  5.000) = 257306 
    [ 5.000,  7.500) = 6237 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =      9.356 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     29.828 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 6.152 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.828 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.727 ±(99.9%) 0.015 ms/op
Iteration   1: 4.659 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  14.733 ms/op
                 listUser·p0.9999: 17.384 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 4.658 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  14.473 ms/op
                 listUser·p0.9999: 19.711 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   3: 4.372 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  19.769 ms/op
                 listUser·p0.9999: 28.498 ms/op
                 listUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 210571
  mean =      4.559 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1251 
    [ 2.500,  5.000) = 164989 
    [ 5.000,  7.500) = 39777 
    [ 7.500, 10.000) = 3809 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     15.146 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     28.570 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.776 ± 4.779  ops/ms
ClientGrpc.existUser                       thrpt       3   9.565 ± 0.970  ops/ms
ClientGrpc.getUser                         thrpt       3   9.003 ± 0.643  ops/ms
ClientGrpc.listUser                        thrpt       3   6.749 ± 0.788  ops/ms
ClientGrpc.createUser                       avgt       3   3.533 ± 1.611   ms/op
ClientGrpc.existUser                        avgt       3   3.371 ± 2.418   ms/op
ClientGrpc.getUser                          avgt       3   3.459 ± 1.616   ms/op
ClientGrpc.listUser                         avgt       3   4.656 ± 0.925   ms/op
ClientGrpc.createUser                     sample  267820   3.584 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.836           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.808           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.245           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.373           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.054           ms/op
ClientGrpc.existUser                      sample  284949   3.369 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.719           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.652           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.203           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.759           ms/op
ClientGrpc.getUser                        sample  272984   3.517 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.697           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.356           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.525           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.917           ms/op
ClientGrpc.listUser                       sample  210571   4.559 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.094           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.358           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.146           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.378           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
