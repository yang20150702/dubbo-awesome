# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.052 ops/ms
# Warmup Iteration   2: 2.271 ops/ms
# Warmup Iteration   3: 5.180 ops/ms
Iteration   1: 5.365 ops/ms
Iteration   2: 5.548 ops/ms
Iteration   3: 5.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.555 ±(99.9%) 3.525 ops/ms [Average]
  (min, avg, max) = (5.365, 5.555, 5.752), stdev = 0.193
  CI (99.9%): [2.030, 9.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.656 ops/ms
# Warmup Iteration   2: 4.787 ops/ms
# Warmup Iteration   3: 5.985 ops/ms
Iteration   1: 5.987 ops/ms
Iteration   2: 5.809 ops/ms
Iteration   3: 5.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.914 ±(99.9%) 1.704 ops/ms [Average]
  (min, avg, max) = (5.809, 5.914, 5.987), stdev = 0.093
  CI (99.9%): [4.210, 7.618] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.535 ops/ms
# Warmup Iteration   2: 4.378 ops/ms
# Warmup Iteration   3: 6.001 ops/ms
Iteration   1: 5.738 ops/ms
Iteration   2: 5.859 ops/ms
Iteration   3: 5.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.819 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (5.738, 5.819, 5.860), stdev = 0.070
  CI (99.9%): [4.536, 7.102] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.559 ops/ms
# Warmup Iteration   2: 4.063 ops/ms
# Warmup Iteration   3: 4.788 ops/ms
Iteration   1: 4.702 ops/ms
Iteration   2: 4.818 ops/ms
Iteration   3: 5.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.850 ±(99.9%) 3.027 ops/ms [Average]
  (min, avg, max) = (4.702, 4.850, 5.029), stdev = 0.166
  CI (99.9%): [1.823, 7.877] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.114 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.192 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.842 ±(99.9%) 0.015 ms/op
Iteration   1: 5.562 ±(99.9%) 0.011 ms/op
Iteration   2: 5.426 ±(99.9%) 0.014 ms/op
Iteration   3: 5.467 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.485 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (5.426, 5.485, 5.562), stdev = 0.069
  CI (99.9%): [4.218, 6.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.512 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.427 ±(99.9%) 0.009 ms/op
Iteration   1: 5.413 ±(99.9%) 0.011 ms/op
Iteration   2: 5.264 ±(99.9%) 0.013 ms/op
Iteration   3: 5.320 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.332 ±(99.9%) 1.373 ms/op [Average]
  (min, avg, max) = (5.264, 5.332, 5.413), stdev = 0.075
  CI (99.9%): [3.959, 6.705] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.587 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.570 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.950 ±(99.9%) 0.009 ms/op
Iteration   1: 5.821 ±(99.9%) 0.009 ms/op
Iteration   2: 5.438 ±(99.9%) 0.015 ms/op
Iteration   3: 5.870 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.710 ±(99.9%) 4.309 ms/op [Average]
  (min, avg, max) = (5.438, 5.710, 5.870), stdev = 0.236
  CI (99.9%): [1.400, 10.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.772 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 9.039 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.891 ±(99.9%) 0.013 ms/op
Iteration   1: 6.567 ±(99.9%) 0.017 ms/op
Iteration   2: 6.525 ±(99.9%) 0.016 ms/op
Iteration   3: 6.673 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.588 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (6.525, 6.588, 6.673), stdev = 0.076
  CI (99.9%): [5.194, 7.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.486 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 6.970 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.044 ±(99.9%) 0.029 ms/op
Iteration   1: 5.594 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.425 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   8.520 ms/op
                 createUser·p0.99:   11.452 ms/op
                 createUser·p0.999:  24.341 ms/op
                 createUser·p0.9999: 27.356 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   2: 5.578 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   6.881 ms/op
                 createUser·p0.95:   8.290 ms/op
                 createUser·p0.99:   11.665 ms/op
                 createUser·p0.999:  26.706 ms/op
                 createUser·p0.9999: 31.278 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   3: 5.820 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.376 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   8.077 ms/op
                 createUser·p0.99:   12.222 ms/op
                 createUser·p0.999:  27.595 ms/op
                 createUser·p0.9999: 36.340 ms/op
                 createUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169431
  mean =      5.662 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 56364 
    [ 5.000,  7.500) = 100944 
    [ 7.500, 10.000) = 8237 
    [10.000, 12.500) = 2463 
    [12.500, 15.000) = 691 
    [15.000, 17.500) = 431 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.004 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     25.316 ms/op
     p(99.9900) =     34.659 ms/op
     p(99.9990) =     36.831 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.067 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 6.369 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.700 ±(99.9%) 0.024 ms/op
Iteration   1: 5.433 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.619 ms/op
                 existUser·p0.95:   7.528 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  16.433 ms/op
                 existUser·p0.9999: 28.810 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   2: 5.582 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.971 ms/op
                 existUser·p0.95:   8.487 ms/op
                 existUser·p0.99:   12.423 ms/op
                 existUser·p0.999:  29.065 ms/op
                 existUser·p0.9999: 34.406 ms/op
                 existUser·p1.00:   34.472 ms/op

Iteration   3: 5.270 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.564 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   7.479 ms/op
                 existUser·p0.99:   11.796 ms/op
                 existUser·p0.999:  28.945 ms/op
                 existUser·p0.9999: 33.192 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176945
  mean =      5.425 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 77495 
    [ 5.000,  7.500) = 88978 
    [ 7.500, 10.000) = 6984 
    [10.000, 12.500) = 2148 
    [12.500, 15.000) = 750 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.987 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     27.825 ms/op
     p(99.9900) =     33.138 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.329 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 6.916 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.641 ±(99.9%) 0.021 ms/op
Iteration   1: 5.879 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   8.077 ms/op
                 getUser·p0.95:   10.076 ms/op
                 getUser·p0.99:   14.221 ms/op
                 getUser·p0.999:  25.297 ms/op
                 getUser·p0.9999: 30.724 ms/op
                 getUser·p1.00:   32.276 ms/op

Iteration   2: 5.759 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.347 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.094 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   11.469 ms/op
                 getUser·p0.999:  15.794 ms/op
                 getUser·p0.9999: 28.352 ms/op
                 getUser·p1.00:   33.423 ms/op

Iteration   3: 5.633 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.593 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   6.660 ms/op
                 getUser·p0.95:   8.126 ms/op
                 getUser·p0.99:   11.846 ms/op
                 getUser·p0.999:  24.143 ms/op
                 getUser·p0.9999: 28.464 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166716
  mean =      5.755 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 49821 
    [ 5.000,  7.500) = 102440 
    [ 7.500, 10.000) = 8958 
    [10.000, 12.500) = 3646 
    [12.500, 15.000) = 1169 
    [15.000, 17.500) = 337 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     12.747 ms/op
     p(99.9000) =     22.764 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     32.658 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.457 ±(99.9%) 0.374 ms/op
# Warmup Iteration   2: 8.417 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 6.820 ±(99.9%) 0.030 ms/op
Iteration   1: 6.671 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.217 ms/op
                 listUser·p0.95:   10.256 ms/op
                 listUser·p0.99:   13.867 ms/op
                 listUser·p0.999:  29.758 ms/op
                 listUser·p0.9999: 33.554 ms/op
                 listUser·p1.00:   34.472 ms/op

Iteration   2: 6.674 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   6.316 ms/op
                 listUser·p0.90:   7.881 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   13.300 ms/op
                 listUser·p0.999:  29.360 ms/op
                 listUser·p0.9999: 31.195 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   3: 6.642 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.301 ms/op
                 listUser·p0.50:   6.218 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   13.981 ms/op
                 listUser·p0.999:  25.837 ms/op
                 listUser·p0.9999: 36.331 ms/op
                 listUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144021
  mean =      6.662 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 4154 
    [ 5.000,  7.500) = 119636 
    [ 7.500, 10.000) = 13654 
    [10.000, 12.500) = 4090 
    [12.500, 15.000) = 1525 
    [15.000, 17.500) = 370 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 108 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      6.250 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =      9.732 ms/op
     p(99.0000) =     13.763 ms/op
     p(99.9000) =     28.999 ms/op
     p(99.9900) =     35.048 ms/op
     p(99.9990) =     36.884 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.555 ± 3.525  ops/ms
ClientPb.existUser                       thrpt       3   5.914 ± 1.704  ops/ms
ClientPb.getUser                         thrpt       3   5.819 ± 1.283  ops/ms
ClientPb.listUser                        thrpt       3   4.850 ± 3.027  ops/ms
ClientPb.createUser                       avgt       3   5.485 ± 1.267   ms/op
ClientPb.existUser                        avgt       3   5.332 ± 1.373   ms/op
ClientPb.getUser                          avgt       3   5.710 ± 4.309   ms/op
ClientPb.listUser                         avgt       3   6.588 ± 1.394   ms/op
ClientPb.createUser                     sample  169431   5.662 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.591           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.004           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.298           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.764           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.316           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.659           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.831           ms/op
ClientPb.existUser                      sample  176945   5.425 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.452           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.095           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.627           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.987           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.534           ms/op
ClientPb.existUser:existUser·p0.999     sample          27.825           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.138           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  166716   5.755 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.749           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.366           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.184           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.929           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.747           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.764           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.360           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.423           ms/op
ClientPb.listUser                       sample  144021   6.662 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.175           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.250           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.732           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.763           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.999           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.048           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.028           ms/op
