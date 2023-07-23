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
# Warmup Iteration   1: 1.608 ops/ms
# Warmup Iteration   2: 3.675 ops/ms
# Warmup Iteration   3: 7.672 ops/ms
Iteration   1: 8.158 ops/ms
Iteration   2: 8.747 ops/ms
Iteration   3: 8.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.583 ±(99.9%) 6.764 ops/ms [Average]
  (min, avg, max) = (8.158, 8.583, 8.843), stdev = 0.371
  CI (99.9%): [1.819, 15.346] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.568 ops/ms
# Warmup Iteration   2: 8.398 ops/ms
# Warmup Iteration   3: 8.648 ops/ms
Iteration   1: 8.369 ops/ms
Iteration   2: 8.906 ops/ms
Iteration   3: 9.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.759 ±(99.9%) 6.234 ops/ms [Average]
  (min, avg, max) = (8.369, 8.759, 9.004), stdev = 0.342
  CI (99.9%): [2.525, 14.994] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.193 ops/ms
# Warmup Iteration   2: 7.336 ops/ms
# Warmup Iteration   3: 8.856 ops/ms
Iteration   1: 8.219 ops/ms
Iteration   2: 8.885 ops/ms
Iteration   3: 9.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.767 ±(99.9%) 9.113 ops/ms [Average]
  (min, avg, max) = (8.219, 8.767, 9.196), stdev = 0.500
  CI (99.9%): [≈ 0, 17.880] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.234 ops/ms
# Warmup Iteration   2: 6.572 ops/ms
# Warmup Iteration   3: 7.383 ops/ms
Iteration   1: 7.512 ops/ms
Iteration   2: 7.215 ops/ms
Iteration   3: 7.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.366 ±(99.9%) 2.711 ops/ms [Average]
  (min, avg, max) = (7.215, 7.366, 7.512), stdev = 0.149
  CI (99.9%): [4.655, 10.076] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.068 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.007 ms/op
Iteration   1: 3.597 ±(99.9%) 0.008 ms/op
Iteration   2: 3.600 ±(99.9%) 0.018 ms/op
Iteration   3: 3.887 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.695 ±(99.9%) 3.036 ms/op [Average]
  (min, avg, max) = (3.597, 3.695, 3.887), stdev = 0.166
  CI (99.9%): [0.659, 6.731] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.359 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.004 ms/op
Iteration   1: 3.479 ±(99.9%) 0.012 ms/op
Iteration   2: 3.347 ±(99.9%) 0.011 ms/op
Iteration   3: 3.404 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.410 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (3.347, 3.410, 3.479), stdev = 0.066
  CI (99.9%): [2.200, 4.620] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.373 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.004 ms/op
Iteration   1: 3.750 ±(99.9%) 0.005 ms/op
Iteration   2: 3.561 ±(99.9%) 0.009 ms/op
Iteration   3: 3.576 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.629 ±(99.9%) 1.917 ms/op [Average]
  (min, avg, max) = (3.561, 3.629, 3.750), stdev = 0.105
  CI (99.9%): [1.712, 5.546] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 14.001 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.010 ms/op
Iteration   1: 4.489 ±(99.9%) 0.006 ms/op
Iteration   2: 4.429 ±(99.9%) 0.011 ms/op
Iteration   3: 4.404 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.440 ±(99.9%) 0.797 ms/op [Average]
  (min, avg, max) = (4.404, 4.440, 4.489), stdev = 0.044
  CI (99.9%): [3.643, 5.237] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.804 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.017 ms/op
Iteration   1: 3.692 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.989 ms/op
                 createUser·p0.999:  12.058 ms/op
                 createUser·p0.9999: 29.524 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   2: 3.917 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  24.665 ms/op
                 createUser·p0.9999: 45.875 ms/op
                 createUser·p1.00:   46.727 ms/op

Iteration   3: 3.847 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   8.118 ms/op
                 createUser·p0.999:  25.723 ms/op
                 createUser·p0.9999: 30.660 ms/op
                 createUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 251561
  mean =      3.816 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 239886 
    [ 5.000, 10.000) = 11069 
    [10.000, 15.000) = 259 
    [15.000, 20.000) = 67 
    [20.000, 25.000) = 91 
    [25.000, 30.000) = 124 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     22.794 ms/op
     p(99.9900) =     44.145 ms/op
     p(99.9990) =     46.135 ms/op
     p(99.9999) =     46.727 ms/op
    p(100.0000) =     46.727 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.546 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.012 ms/op
Iteration   1: 3.463 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  12.756 ms/op
                 existUser·p0.9999: 24.117 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   2: 3.569 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  21.970 ms/op
                 existUser·p0.9999: 25.759 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.590 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  10.895 ms/op
                 existUser·p0.9999: 29.363 ms/op
                 existUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271117
  mean =      3.540 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2883 
    [ 2.500,  5.000) = 259153 
    [ 5.000,  7.500) = 7761 
    [ 7.500, 10.000) = 824 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     12.565 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.905 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.280 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.014 ms/op
Iteration   1: 3.868 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  20.881 ms/op
                 getUser·p0.9999: 23.322 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.604 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  11.174 ms/op
                 getUser·p0.9999: 22.745 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.791 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  23.912 ms/op
                 getUser·p0.9999: 27.507 ms/op
                 getUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 255726
  mean =      3.751 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 731 
    [ 2.500,  5.000) = 242883 
    [ 5.000,  7.500) = 9173 
    [ 7.500, 10.000) = 2255 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     19.670 ms/op
     p(99.9900) =     26.687 ms/op
     p(99.9990) =     27.835 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 14.431 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 5.520 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.463 ±(99.9%) 0.016 ms/op
Iteration   1: 4.414 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  22.071 ms/op
                 listUser·p0.9999: 31.860 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   2: 4.294 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 21.958 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 4.257 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.590 ms/op
                 listUser·p0.9999: 20.593 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222125
  mean =      4.320 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 208643 
    [ 5.000,  7.500) = 9111 
    [ 7.500, 10.000) = 3111 
    [10.000, 12.500) = 682 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     17.752 ms/op
     p(99.9900) =     25.126 ms/op
     p(99.9990) =     32.189 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.583 ± 6.764  ops/ms
ClientPb.existUser                       thrpt       3   8.759 ± 6.234  ops/ms
ClientPb.getUser                         thrpt       3   8.767 ± 9.113  ops/ms
ClientPb.listUser                        thrpt       3   7.366 ± 2.711  ops/ms
ClientPb.createUser                       avgt       3   3.695 ± 3.036   ms/op
ClientPb.existUser                        avgt       3   3.410 ± 1.210   ms/op
ClientPb.getUser                          avgt       3   3.629 ± 1.917   ms/op
ClientPb.listUser                         avgt       3   4.440 ± 0.797   ms/op
ClientPb.createUser                     sample  251561   3.816 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.642           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.422           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.794           ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.145           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.727           ms/op
ClientPb.existUser                      sample  271117   3.540 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.980           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.404           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.565           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.213           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.965           ms/op
ClientPb.getUser                        sample  255726   3.751 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.709           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.670           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.687           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.180           ms/op
ClientPb.listUser                       sample  222125   4.320 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.966           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.752           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.126           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.342           ms/op
