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
# Warmup Iteration   1: 1.158 ops/ms
# Warmup Iteration   2: 2.795 ops/ms
# Warmup Iteration   3: 5.767 ops/ms
Iteration   1: 6.044 ops/ms
Iteration   2: 6.407 ops/ms
Iteration   3: 6.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.288 ±(99.9%) 3.853 ops/ms [Average]
  (min, avg, max) = (6.044, 6.288, 6.412), stdev = 0.211
  CI (99.9%): [2.435, 10.141] (assumes normal distribution)


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
# Warmup Iteration   1: 1.857 ops/ms
# Warmup Iteration   2: 5.237 ops/ms
# Warmup Iteration   3: 6.732 ops/ms
Iteration   1: 6.629 ops/ms
Iteration   2: 6.559 ops/ms
Iteration   3: 6.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.591 ±(99.9%) 0.653 ops/ms [Average]
  (min, avg, max) = (6.559, 6.591, 6.629), stdev = 0.036
  CI (99.9%): [5.938, 7.243] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.732 ops/ms
# Warmup Iteration   2: 5.094 ops/ms
# Warmup Iteration   3: 6.208 ops/ms
Iteration   1: 6.421 ops/ms
Iteration   2: 6.252 ops/ms
Iteration   3: 6.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.264 ±(99.9%) 2.764 ops/ms [Average]
  (min, avg, max) = (6.118, 6.264, 6.421), stdev = 0.151
  CI (99.9%): [3.500, 9.028] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.546 ops/ms
# Warmup Iteration   2: 4.691 ops/ms
# Warmup Iteration   3: 5.508 ops/ms
Iteration   1: 5.464 ops/ms
Iteration   2: 5.495 ops/ms
Iteration   3: 5.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.469 ±(99.9%) 0.434 ops/ms [Average]
  (min, avg, max) = (5.448, 5.469, 5.495), stdev = 0.024
  CI (99.9%): [5.035, 5.903] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.424 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.637 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.445 ±(99.9%) 0.009 ms/op
Iteration   1: 5.308 ±(99.9%) 0.014 ms/op
Iteration   2: 4.989 ±(99.9%) 0.022 ms/op
Iteration   3: 5.115 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.137 ±(99.9%) 2.925 ms/op [Average]
  (min, avg, max) = (4.989, 5.137, 5.308), stdev = 0.160
  CI (99.9%): [2.212, 8.063] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 15.198 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.355 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.138 ±(99.9%) 0.009 ms/op
Iteration   1: 4.797 ±(99.9%) 0.014 ms/op
Iteration   2: 4.945 ±(99.9%) 0.013 ms/op
Iteration   3: 4.783 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.842 ±(99.9%) 1.636 ms/op [Average]
  (min, avg, max) = (4.783, 4.842, 4.945), stdev = 0.090
  CI (99.9%): [3.206, 6.477] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.084 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.519 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.967 ±(99.9%) 0.017 ms/op
Iteration   1: 5.291 ±(99.9%) 0.008 ms/op
Iteration   2: 5.141 ±(99.9%) 0.009 ms/op
Iteration   3: 5.109 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.181 ±(99.9%) 1.775 ms/op [Average]
  (min, avg, max) = (5.109, 5.181, 5.291), stdev = 0.097
  CI (99.9%): [3.406, 6.955] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.025 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 7.238 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.078 ±(99.9%) 0.012 ms/op
Iteration   1: 5.774 ±(99.9%) 0.021 ms/op
Iteration   2: 6.068 ±(99.9%) 0.009 ms/op
Iteration   3: 5.766 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.869 ±(99.9%) 3.134 ms/op [Average]
  (min, avg, max) = (5.766, 5.869, 6.068), stdev = 0.172
  CI (99.9%): [2.735, 9.003] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.598 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.191 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.377 ±(99.9%) 0.022 ms/op
Iteration   1: 5.131 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  20.480 ms/op
                 createUser·p0.9999: 24.379 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 5.182 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.644 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 25.619 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 5.053 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   5.939 ms/op
                 createUser·p0.95:   6.504 ms/op
                 createUser·p0.99:   9.388 ms/op
                 createUser·p0.999:  24.171 ms/op
                 createUser·p0.9999: 28.215 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 187263
  mean =      5.122 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 108290 
    [ 5.000,  7.500) = 74928 
    [ 7.500, 10.000) = 2625 
    [10.000, 12.500) = 709 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     20.602 ms/op
     p(99.9900) =     27.239 ms/op
     p(99.9990) =     29.447 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 15.165 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.908 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.232 ±(99.9%) 0.019 ms/op
Iteration   1: 4.855 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.911 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   5.816 ms/op
                 existUser·p0.95:   6.455 ms/op
                 existUser·p0.99:   8.618 ms/op
                 existUser·p0.999:  15.227 ms/op
                 existUser·p0.9999: 27.276 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   2: 4.744 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.226 ms/op
                 existUser·p0.99:   8.274 ms/op
                 existUser·p0.999:  12.478 ms/op
                 existUser·p0.9999: 27.099 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 4.720 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   8.938 ms/op
                 existUser·p0.999:  16.446 ms/op
                 existUser·p0.9999: 29.302 ms/op
                 existUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 201026
  mean =      4.772 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 158750 
    [ 5.000,  7.500) = 38323 
    [ 7.500, 10.000) = 2884 
    [10.000, 12.500) = 657 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     28.498 ms/op
     p(99.9990) =     30.205 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 17.306 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.093 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.160 ±(99.9%) 0.016 ms/op
Iteration   1: 5.153 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.437 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.169 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  22.577 ms/op
                 getUser·p0.9999: 26.116 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   2: 4.960 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.171 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.439 ms/op
                 getUser·p0.99:   9.044 ms/op
                 getUser·p0.999:  21.605 ms/op
                 getUser·p0.9999: 27.266 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 5.204 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   5.063 ms/op
                 getUser·p0.90:   5.849 ms/op
                 getUser·p0.95:   6.439 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  25.073 ms/op
                 getUser·p0.9999: 29.702 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 188004
  mean =      5.103 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 111018 
    [ 5.000,  7.500) = 71389 
    [ 7.500, 10.000) = 4267 
    [10.000, 12.500) = 876 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.062 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     30.195 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 18.534 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 6.613 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.133 ±(99.9%) 0.021 ms/op
Iteration   1: 5.975 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   6.734 ms/op
                 listUser·p0.95:   7.463 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  26.700 ms/op
                 listUser·p0.9999: 28.951 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   2: 5.934 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   10.300 ms/op
                 listUser·p0.999:  26.118 ms/op
                 listUser·p0.9999: 34.397 ms/op
                 listUser·p1.00:   35.389 ms/op

Iteration   3: 5.765 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   11.259 ms/op
                 listUser·p0.999:  19.629 ms/op
                 listUser·p0.9999: 31.265 ms/op
                 listUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 162958
  mean =      5.890 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 11590 
    [ 5.000,  7.500) = 144111 
    [ 7.500, 10.000) = 5025 
    [10.000, 12.500) = 1417 
    [12.500, 15.000) = 390 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.735 ms/op
     p(50.0000) =      5.677 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =     10.640 ms/op
     p(99.9000) =     25.756 ms/op
     p(99.9900) =     32.972 ms/op
     p(99.9990) =     35.348 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.288 ± 3.853  ops/ms
ClientPb.existUser                       thrpt       3   6.591 ± 0.653  ops/ms
ClientPb.getUser                         thrpt       3   6.264 ± 2.764  ops/ms
ClientPb.listUser                        thrpt       3   5.469 ± 0.434  ops/ms
ClientPb.createUser                       avgt       3   5.137 ± 2.925   ms/op
ClientPb.existUser                        avgt       3   4.842 ± 1.636   ms/op
ClientPb.getUser                          avgt       3   5.181 ± 1.775   ms/op
ClientPb.listUser                         avgt       3   5.869 ± 3.134   ms/op
ClientPb.createUser                     sample  187263   5.122 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.450           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.595           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.208           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.602           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.239           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.590           ms/op
ClientPb.existUser                      sample  201026   4.772 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.546           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.571           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.226           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.503           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.269           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.498           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.212           ms/op
ClientPb.getUser                        sample  188004   5.103 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.062           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.882           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.931           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.372           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.610           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.310           ms/op
ClientPb.listUser                       sample  162958   5.890 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.735           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.640           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.756           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.972           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.389           ms/op
