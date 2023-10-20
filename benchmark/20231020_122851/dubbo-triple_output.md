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
# Warmup Iteration   1: 1.133 ops/ms
# Warmup Iteration   2: 2.628 ops/ms
# Warmup Iteration   3: 5.408 ops/ms
Iteration   1: 5.974 ops/ms
Iteration   2: 6.102 ops/ms
Iteration   3: 6.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.083 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (5.974, 6.083, 6.171), stdev = 0.100
  CI (99.9%): [4.261, 7.904] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.862 ops/ms
# Warmup Iteration   2: 5.023 ops/ms
# Warmup Iteration   3: 6.148 ops/ms
Iteration   1: 6.499 ops/ms
Iteration   2: 6.538 ops/ms
Iteration   3: 6.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.528 ±(99.9%) 0.465 ops/ms [Average]
  (min, avg, max) = (6.499, 6.528, 6.546), stdev = 0.025
  CI (99.9%): [6.063, 6.992] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.658 ops/ms
# Warmup Iteration   2: 4.483 ops/ms
# Warmup Iteration   3: 5.913 ops/ms
Iteration   1: 5.793 ops/ms
Iteration   2: 5.883 ops/ms
Iteration   3: 6.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.956 ±(99.9%) 3.823 ops/ms [Average]
  (min, avg, max) = (5.793, 5.956, 6.193), stdev = 0.210
  CI (99.9%): [2.133, 9.779] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.726 ops/ms
# Warmup Iteration   2: 4.512 ops/ms
# Warmup Iteration   3: 5.218 ops/ms
Iteration   1: 5.379 ops/ms
Iteration   2: 5.357 ops/ms
Iteration   3: 5.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.304 ±(99.9%) 2.039 ops/ms [Average]
  (min, avg, max) = (5.176, 5.304, 5.379), stdev = 0.112
  CI (99.9%): [3.265, 7.343] (assumes normal distribution)


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
# Warmup Iteration   1: 19.568 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.531 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.340 ±(99.9%) 0.013 ms/op
Iteration   1: 5.240 ±(99.9%) 0.010 ms/op
Iteration   2: 5.007 ±(99.9%) 0.007 ms/op
Iteration   3: 5.146 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.131 ±(99.9%) 2.138 ms/op [Average]
  (min, avg, max) = (5.007, 5.131, 5.240), stdev = 0.117
  CI (99.9%): [2.993, 7.270] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.840 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.067 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.114 ±(99.9%) 0.007 ms/op
Iteration   1: 4.981 ±(99.9%) 0.008 ms/op
Iteration   2: 5.074 ±(99.9%) 0.005 ms/op
Iteration   3: 5.032 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.029 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (4.981, 5.029, 5.074), stdev = 0.046
  CI (99.9%): [4.181, 5.876] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 14.940 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.591 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.195 ±(99.9%) 0.007 ms/op
Iteration   1: 5.134 ±(99.9%) 0.008 ms/op
Iteration   2: 5.412 ±(99.9%) 0.005 ms/op
Iteration   3: 4.970 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.172 ±(99.9%) 4.081 ms/op [Average]
  (min, avg, max) = (4.970, 5.172, 5.412), stdev = 0.224
  CI (99.9%): [1.092, 9.253] (assumes normal distribution)


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
# Warmup Iteration   1: 19.284 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.179 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.099 ±(99.9%) 0.009 ms/op
Iteration   1: 5.924 ±(99.9%) 0.010 ms/op
Iteration   2: 5.851 ±(99.9%) 0.010 ms/op
Iteration   3: 5.705 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.827 ±(99.9%) 2.031 ms/op [Average]
  (min, avg, max) = (5.705, 5.827, 5.924), stdev = 0.111
  CI (99.9%): [3.796, 7.858] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.866 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.130 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.577 ±(99.9%) 0.023 ms/op
Iteration   1: 5.468 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  22.262 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 5.340 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.025 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 32.476 ms/op
                 createUser·p1.00:   33.161 ms/op

Iteration   3: 5.247 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.398 ms/op
                 createUser·p0.95:   6.799 ms/op
                 createUser·p0.99:   8.733 ms/op
                 createUser·p0.999:  28.050 ms/op
                 createUser·p0.9999: 31.212 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179389
  mean =      5.350 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 81844 
    [ 5.000,  7.500) = 90772 
    [ 7.500, 10.000) = 5336 
    [10.000, 12.500) = 671 
    [12.500, 15.000) = 309 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.675 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.135 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     24.760 ms/op
     p(99.9900) =     31.074 ms/op
     p(99.9990) =     33.031 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.613 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 5.488 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.096 ±(99.9%) 0.019 ms/op
Iteration   1: 4.907 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.175 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   5.915 ms/op
                 existUser·p0.95:   6.521 ms/op
                 existUser·p0.99:   8.421 ms/op
                 existUser·p0.999:  13.625 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 4.798 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   4.588 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.152 ms/op
                 existUser·p0.99:   8.424 ms/op
                 existUser·p0.999:  20.546 ms/op
                 existUser·p0.9999: 24.456 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 4.938 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  22.192 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 196626
  mean =      4.880 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 137752 
    [ 5.000,  7.500) = 54539 
    [ 7.500, 10.000) = 3249 
    [10.000, 12.500) = 543 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     20.492 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     25.856 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.888 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 6.044 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.012 ±(99.9%) 0.015 ms/op
Iteration   1: 5.358 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.576 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   6.963 ms/op
                 getUser·p0.95:   7.750 ms/op
                 getUser·p0.99:   12.075 ms/op
                 getUser·p0.999:  21.506 ms/op
                 getUser·p0.9999: 24.449 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   2: 5.567 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   7.193 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   11.354 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 29.106 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 5.039 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.540 ms/op
                 getUser·p0.50:   4.841 ms/op
                 getUser·p0.90:   5.865 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  24.525 ms/op
                 getUser·p0.9999: 27.983 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180626
  mean =      5.312 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 91719 
    [ 5.000,  7.500) = 78893 
    [ 7.500, 10.000) = 7290 
    [10.000, 12.500) = 1793 
    [12.500, 15.000) = 586 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     28.338 ms/op
     p(99.9990) =     30.186 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 15.987 ±(99.9%) 0.270 ms/op
# Warmup Iteration   2: 6.850 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.064 ±(99.9%) 0.022 ms/op
Iteration   1: 5.802 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  23.265 ms/op
                 listUser·p0.9999: 26.573 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   2: 5.851 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.818 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   11.020 ms/op
                 listUser·p0.999:  25.463 ms/op
                 listUser·p0.9999: 27.185 ms/op
                 listUser·p1.00:   29.753 ms/op

Iteration   3: 5.768 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   10.220 ms/op
                 listUser·p0.999:  18.759 ms/op
                 listUser·p0.9999: 29.084 ms/op
                 listUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 165279
  mean =      5.807 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 19301 
    [ 5.000,  7.500) = 138132 
    [ 7.500, 10.000) = 5899 
    [10.000, 12.500) = 1273 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 99 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     23.771 ms/op
     p(99.9900) =     27.620 ms/op
     p(99.9990) =     29.874 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.083 ± 1.822  ops/ms
ClientPb.existUser                       thrpt       3   6.528 ± 0.465  ops/ms
ClientPb.getUser                         thrpt       3   5.956 ± 3.823  ops/ms
ClientPb.listUser                        thrpt       3   5.304 ± 2.039  ops/ms
ClientPb.createUser                       avgt       3   5.131 ± 2.138   ms/op
ClientPb.existUser                        avgt       3   5.029 ± 0.847   ms/op
ClientPb.getUser                          avgt       3   5.172 ± 4.081   ms/op
ClientPb.listUser                         avgt       3   5.827 ± 2.031   ms/op
ClientPb.createUser                     sample  179389   5.350 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.675           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.095           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.496           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.135           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.503           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.760           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.161           ms/op
ClientPb.existUser                      sample  196626   4.880 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.175           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.653           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.569           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.492           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.919           ms/op
ClientPb.getUser                        sample  180626   5.312 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.830           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.823           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.338           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.212           ms/op
ClientPb.listUser                       sample  165279   5.807 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.415           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.652           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.338           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.771           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.620           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.917           ms/op
