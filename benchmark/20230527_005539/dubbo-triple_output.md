# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.301 ops/ms
# Warmup Iteration   2: 3.364 ops/ms
# Warmup Iteration   3: 5.781 ops/ms
Iteration   1: 5.927 ops/ms
Iteration   2: 6.589 ops/ms
Iteration   3: 6.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.232 ±(99.9%) 6.088 ops/ms [Average]
  (min, avg, max) = (5.927, 6.232, 6.589), stdev = 0.334
  CI (99.9%): [0.144, 12.320] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.980 ops/ms
# Warmup Iteration   2: 6.037 ops/ms
# Warmup Iteration   3: 6.434 ops/ms
Iteration   1: 6.975 ops/ms
Iteration   2: 6.800 ops/ms
Iteration   3: 6.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.812 ±(99.9%) 2.872 ops/ms [Average]
  (min, avg, max) = (6.661, 6.812, 6.975), stdev = 0.157
  CI (99.9%): [3.940, 9.685] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.807 ops/ms
# Warmup Iteration   2: 4.938 ops/ms
# Warmup Iteration   3: 6.100 ops/ms
Iteration   1: 6.263 ops/ms
Iteration   2: 6.194 ops/ms
Iteration   3: 6.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.316 ±(99.9%) 2.842 ops/ms [Average]
  (min, avg, max) = (6.194, 6.316, 6.492), stdev = 0.156
  CI (99.9%): [3.474, 9.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.724 ops/ms
# Warmup Iteration   2: 4.365 ops/ms
# Warmup Iteration   3: 5.317 ops/ms
Iteration   1: 5.616 ops/ms
Iteration   2: 5.470 ops/ms
Iteration   3: 5.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.608 ±(99.9%) 2.447 ops/ms [Average]
  (min, avg, max) = (5.470, 5.608, 5.738), stdev = 0.134
  CI (99.9%): [3.161, 8.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 15.128 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.925 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.024 ±(99.9%) 0.015 ms/op
Iteration   1: 5.019 ±(99.9%) 0.014 ms/op
Iteration   2: 5.100 ±(99.9%) 0.012 ms/op
Iteration   3: 5.179 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.100 ±(99.9%) 1.456 ms/op [Average]
  (min, avg, max) = (5.019, 5.100, 5.179), stdev = 0.080
  CI (99.9%): [3.644, 6.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.817 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.984 ±(99.9%) 0.009 ms/op
Iteration   1: 5.142 ±(99.9%) 0.006 ms/op
Iteration   2: 4.976 ±(99.9%) 0.008 ms/op
Iteration   3: 4.887 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.002 ±(99.9%) 2.357 ms/op [Average]
  (min, avg, max) = (4.887, 5.002, 5.142), stdev = 0.129
  CI (99.9%): [2.645, 7.358] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 14.040 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.334 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.132 ±(99.9%) 0.012 ms/op
Iteration   1: 5.053 ±(99.9%) 0.014 ms/op
Iteration   2: 4.920 ±(99.9%) 0.013 ms/op
Iteration   3: 5.039 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.004 ±(99.9%) 1.334 ms/op [Average]
  (min, avg, max) = (4.920, 5.004, 5.053), stdev = 0.073
  CI (99.9%): [3.670, 6.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.079 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 7.379 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.114 ±(99.9%) 0.010 ms/op
Iteration   1: 6.153 ±(99.9%) 0.020 ms/op
Iteration   2: 6.250 ±(99.9%) 0.012 ms/op
Iteration   3: 5.802 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.069 ±(99.9%) 4.299 ms/op [Average]
  (min, avg, max) = (5.802, 6.069, 6.250), stdev = 0.236
  CI (99.9%): [1.770, 10.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.189 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 6.336 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.521 ±(99.9%) 0.026 ms/op
Iteration   1: 5.314 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  23.790 ms/op
                 createUser·p0.9999: 30.867 ms/op
                 createUser·p1.00:   31.850 ms/op

Iteration   2: 5.354 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.175 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.463 ms/op
                 createUser·p0.99:   9.931 ms/op
                 createUser·p0.999:  29.562 ms/op
                 createUser·p0.9999: 37.357 ms/op
                 createUser·p1.00:   37.683 ms/op

Iteration   3: 4.910 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   6.046 ms/op
                 createUser·p0.95:   6.685 ms/op
                 createUser·p0.99:   8.364 ms/op
                 createUser·p0.999:  17.320 ms/op
                 createUser·p0.9999: 38.535 ms/op
                 createUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185208
  mean =      5.185 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 99164 
    [ 5.000,  7.500) = 78287 
    [ 7.500, 10.000) = 6367 
    [10.000, 12.500) = 903 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     24.038 ms/op
     p(99.9900) =     37.356 ms/op
     p(99.9990) =     39.098 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.530 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.662 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.017 ms/op
Iteration   1: 4.984 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   7.004 ms/op
                 existUser·p0.99:   9.162 ms/op
                 existUser·p0.999:  20.613 ms/op
                 existUser·p0.9999: 26.741 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   2: 4.690 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.954 ms/op
                 existUser·p0.50:   4.497 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.423 ms/op
                 existUser·p0.99:   9.028 ms/op
                 existUser·p0.999:  15.087 ms/op
                 existUser·p0.9999: 23.676 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 4.857 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.001 ms/op
                 existUser·p0.50:   4.653 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.586 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  16.630 ms/op
                 existUser·p0.9999: 27.107 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 198127
  mean =      4.841 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 136156 
    [ 5.000,  7.500) = 56398 
    [ 7.500, 10.000) = 4167 
    [10.000, 12.500) = 870 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.717 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     16.593 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     28.478 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.159 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.638 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.053 ±(99.9%) 0.017 ms/op
Iteration   1: 5.039 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.695 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.240 ms/op
                 getUser·p0.95:   6.963 ms/op
                 getUser·p0.99:   9.486 ms/op
                 getUser·p0.999:  24.129 ms/op
                 getUser·p0.9999: 29.019 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   2: 5.000 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.962 ms/op
                 getUser·p0.50:   4.768 ms/op
                 getUser·p0.90:   6.046 ms/op
                 getUser·p0.95:   7.062 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  25.462 ms/op
                 getUser·p0.9999: 29.445 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 4.890 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.191 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.521 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  13.091 ms/op
                 getUser·p0.9999: 30.981 ms/op
                 getUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192836
  mean =      4.975 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 121064 
    [ 5.000,  7.500) = 65412 
    [ 7.500, 10.000) = 5069 
    [10.000, 12.500) = 879 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.962 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     24.936 ms/op
     p(99.9900) =     29.636 ms/op
     p(99.9990) =     31.219 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.528 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 6.835 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.996 ±(99.9%) 0.023 ms/op
Iteration   1: 5.855 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.741 ms/op
                 listUser·p0.99:   10.844 ms/op
                 listUser·p0.999:  23.271 ms/op
                 listUser·p0.9999: 30.623 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   2: 5.735 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   6.832 ms/op
                 listUser·p0.95:   7.569 ms/op
                 listUser·p0.99:   10.362 ms/op
                 listUser·p0.999:  25.199 ms/op
                 listUser·p0.9999: 27.762 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   3: 5.944 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.064 ms/op
                 listUser·p0.50:   5.628 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.427 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  21.430 ms/op
                 listUser·p0.9999: 24.261 ms/op
                 listUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164296
  mean =      5.843 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 31779 
    [ 5.000,  7.500) = 122247 
    [ 7.500, 10.000) = 7530 
    [10.000, 12.500) = 1783 
    [12.500, 15.000) = 432 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.942 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     23.223 ms/op
     p(99.9900) =     29.453 ms/op
     p(99.9990) =     31.298 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.232 ± 6.088  ops/ms
ClientPb.existUser                       thrpt       3   6.812 ± 2.872  ops/ms
ClientPb.getUser                         thrpt       3   6.316 ± 2.842  ops/ms
ClientPb.listUser                        thrpt       3   5.608 ± 2.447  ops/ms
ClientPb.createUser                       avgt       3   5.100 ± 1.456   ms/op
ClientPb.existUser                        avgt       3   5.002 ± 2.357   ms/op
ClientPb.getUser                          avgt       3   5.004 ± 1.334   ms/op
ClientPb.listUser                         avgt       3   6.069 ± 4.299   ms/op
ClientPb.createUser                     sample  185208   5.185 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.757           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.242           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.421           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.356           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.322           ms/op
ClientPb.existUser                      sample  198127   4.841 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.954           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.915           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.717           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.978           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.593           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.870           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  192836   4.975 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.962           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.175           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.936           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.636           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.523           ms/op
ClientPb.listUser                       sample  164296   5.843 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.942           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.889           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.994           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.223           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.453           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.014           ms/op
