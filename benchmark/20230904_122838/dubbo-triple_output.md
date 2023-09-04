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
# Warmup Iteration   1: 1.038 ops/ms
# Warmup Iteration   2: 2.246 ops/ms
# Warmup Iteration   3: 4.732 ops/ms
Iteration   1: 5.374 ops/ms
Iteration   2: 5.338 ops/ms
Iteration   3: 5.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.505 ±(99.9%) 4.705 ops/ms [Average]
  (min, avg, max) = (5.338, 5.505, 5.802), stdev = 0.258
  CI (99.9%): [0.800, 10.210] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.509 ops/ms
# Warmup Iteration   2: 4.656 ops/ms
# Warmup Iteration   3: 5.648 ops/ms
Iteration   1: 5.796 ops/ms
Iteration   2: 5.786 ops/ms
Iteration   3: 5.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.816 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (5.786, 5.816, 5.866), stdev = 0.044
  CI (99.9%): [5.014, 6.618] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.423 ops/ms
# Warmup Iteration   2: 4.382 ops/ms
# Warmup Iteration   3: 5.569 ops/ms
Iteration   1: 5.613 ops/ms
Iteration   2: 5.728 ops/ms
Iteration   3: 5.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.657 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (5.613, 5.657, 5.728), stdev = 0.062
  CI (99.9%): [4.525, 6.789] (assumes normal distribution)


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
# Warmup Iteration   1: 1.329 ops/ms
# Warmup Iteration   2: 3.739 ops/ms
# Warmup Iteration   3: 4.642 ops/ms
Iteration   1: 4.551 ops/ms
Iteration   2: 4.537 ops/ms
Iteration   3: 4.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.630 ±(99.9%) 2.725 ops/ms [Average]
  (min, avg, max) = (4.537, 4.630, 4.803), stdev = 0.149
  CI (99.9%): [1.905, 7.355] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.409 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 7.235 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.105 ±(99.9%) 0.008 ms/op
Iteration   1: 6.014 ±(99.9%) 0.015 ms/op
Iteration   2: 5.864 ±(99.9%) 0.013 ms/op
Iteration   3: 5.892 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.923 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (5.864, 5.923, 6.014), stdev = 0.080
  CI (99.9%): [4.460, 7.386] (assumes normal distribution)


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
# Warmup Iteration   1: 19.558 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.968 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.695 ±(99.9%) 0.008 ms/op
Iteration   1: 5.352 ±(99.9%) 0.007 ms/op
Iteration   2: 5.584 ±(99.9%) 0.008 ms/op
Iteration   3: 5.436 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.457 ±(99.9%) 2.140 ms/op [Average]
  (min, avg, max) = (5.352, 5.457, 5.584), stdev = 0.117
  CI (99.9%): [3.317, 7.598] (assumes normal distribution)


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
# Warmup Iteration   1: 19.825 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.986 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.981 ±(99.9%) 0.010 ms/op
Iteration   1: 6.319 ±(99.9%) 0.010 ms/op
Iteration   2: 6.014 ±(99.9%) 0.010 ms/op
Iteration   3: 5.850 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.061 ±(99.9%) 4.345 ms/op [Average]
  (min, avg, max) = (5.850, 6.061, 6.319), stdev = 0.238
  CI (99.9%): [1.716, 10.406] (assumes normal distribution)


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
# Warmup Iteration   1: 20.314 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 8.624 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.991 ±(99.9%) 0.012 ms/op
Iteration   1: 6.840 ±(99.9%) 0.013 ms/op
Iteration   2: 6.772 ±(99.9%) 0.013 ms/op
Iteration   3: 6.632 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.748 ±(99.9%) 1.933 ms/op [Average]
  (min, avg, max) = (6.632, 6.748, 6.840), stdev = 0.106
  CI (99.9%): [4.815, 8.680] (assumes normal distribution)


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
# Warmup Iteration   1: 20.690 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.273 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.281 ±(99.9%) 0.032 ms/op
Iteration   1: 5.816 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.518 ms/op
                 createUser·p0.999:  25.294 ms/op
                 createUser·p0.9999: 29.098 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   2: 5.852 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   5.521 ms/op
                 createUser·p0.90:   7.209 ms/op
                 createUser·p0.95:   8.266 ms/op
                 createUser·p0.99:   11.796 ms/op
                 createUser·p0.999:  29.894 ms/op
                 createUser·p0.9999: 33.146 ms/op
                 createUser·p1.00:   33.325 ms/op

Iteration   3: 5.914 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.576 ms/op
                 createUser·p0.50:   5.628 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.274 ms/op
                 createUser·p0.99:   11.027 ms/op
                 createUser·p0.999:  30.015 ms/op
                 createUser·p0.9999: 44.433 ms/op
                 createUser·p1.00:   44.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163840
  mean =      5.860 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 43087 
    [ 5.000, 10.000) = 117646 
    [10.000, 15.000) = 2639 
    [15.000, 20.000) = 241 
    [20.000, 25.000) = 38 
    [25.000, 30.000) = 84 
    [30.000, 35.000) = 85 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.241 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.323 ms/op
     p(99.0000) =     11.502 ms/op
     p(99.9000) =     26.906 ms/op
     p(99.9900) =     43.909 ms/op
     p(99.9990) =     44.790 ms/op
     p(99.9999) =     44.958 ms/op
    p(100.0000) =     44.958 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.553 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 8.378 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 5.718 ±(99.9%) 0.024 ms/op
Iteration   1: 5.720 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   5.202 ms/op
                 existUser·p0.90:   7.561 ms/op
                 existUser·p0.95:   8.978 ms/op
                 existUser·p0.99:   12.321 ms/op
                 existUser·p0.999:  24.615 ms/op
                 existUser·p0.9999: 29.624 ms/op
                 existUser·p1.00:   30.638 ms/op

Iteration   2: 5.576 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   7.184 ms/op
                 existUser·p0.95:   8.282 ms/op
                 existUser·p0.99:   11.092 ms/op
                 existUser·p0.999:  28.317 ms/op
                 existUser·p0.9999: 32.866 ms/op
                 existUser·p1.00:   33.522 ms/op

Iteration   3: 5.529 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.310 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   7.217 ms/op
                 existUser·p0.95:   8.339 ms/op
                 existUser·p0.99:   11.586 ms/op
                 existUser·p0.999:  17.731 ms/op
                 existUser·p0.9999: 35.739 ms/op
                 existUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171243
  mean =      5.607 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 70912 
    [ 5.000,  7.500) = 85020 
    [ 7.500, 10.000) = 11503 
    [10.000, 12.500) = 2511 
    [12.500, 15.000) = 766 
    [15.000, 17.500) = 272 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     21.775 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 21.114 ±(99.9%) 0.400 ms/op
# Warmup Iteration   2: 7.349 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.978 ±(99.9%) 0.024 ms/op
Iteration   1: 5.788 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.531 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   7.471 ms/op
                 getUser·p0.95:   8.733 ms/op
                 getUser·p0.99:   12.222 ms/op
                 getUser·p0.999:  26.198 ms/op
                 getUser·p0.9999: 30.752 ms/op
                 getUser·p1.00:   32.047 ms/op

Iteration   2: 5.510 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.866 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   7.062 ms/op
                 getUser·p0.95:   8.315 ms/op
                 getUser·p0.99:   12.288 ms/op
                 getUser·p0.999:  30.824 ms/op
                 getUser·p0.9999: 33.252 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   3: 5.566 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   7.143 ms/op
                 getUser·p0.95:   8.315 ms/op
                 getUser·p0.99:   11.266 ms/op
                 getUser·p0.999:  30.759 ms/op
                 getUser·p0.9999: 38.470 ms/op
                 getUser·p1.00:   38.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170822
  mean =      5.619 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 68514 
    [ 5.000,  7.500) = 87556 
    [ 7.500, 10.000) = 10997 
    [10.000, 12.500) = 2365 
    [12.500, 15.000) = 848 
    [15.000, 17.500) = 294 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.866 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.977 ms/op
     p(99.9000) =     29.235 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     38.715 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


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
# Warmup Iteration   1: 20.719 ±(99.9%) 0.415 ms/op
# Warmup Iteration   2: 8.892 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 6.821 ±(99.9%) 0.034 ms/op
Iteration   1: 6.866 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.408 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   13.861 ms/op
                 listUser·p0.999:  28.633 ms/op
                 listUser·p0.9999: 36.899 ms/op
                 listUser·p1.00:   37.945 ms/op

Iteration   2: 6.970 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.211 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   9.060 ms/op
                 listUser·p0.95:   10.289 ms/op
                 listUser·p0.99:   13.582 ms/op
                 listUser·p0.999:  30.856 ms/op
                 listUser·p0.9999: 40.763 ms/op
                 listUser·p1.00:   41.288 ms/op

Iteration   3: 7.167 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   6.521 ms/op
                 listUser·p0.90:   9.617 ms/op
                 listUser·p0.95:   11.403 ms/op
                 listUser·p0.99:   14.778 ms/op
                 listUser·p0.999:  31.395 ms/op
                 listUser·p0.9999: 34.678 ms/op
                 listUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137060
  mean =      6.999 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3265 
    [ 5.000, 10.000) = 124628 
    [10.000, 15.000) = 8349 
    [15.000, 20.000) = 530 
    [20.000, 25.000) = 52 
    [25.000, 30.000) = 89 
    [30.000, 35.000) = 101 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.220 ms/op
     p(50.0000) =      6.431 ms/op
     p(90.0000) =      9.191 ms/op
     p(95.0000) =     10.699 ms/op
     p(99.0000) =     14.097 ms/op
     p(99.9000) =     30.603 ms/op
     p(99.9900) =     40.174 ms/op
     p(99.9990) =     41.239 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.505 ± 4.705  ops/ms
ClientPb.existUser                       thrpt       3   5.816 ± 0.802  ops/ms
ClientPb.getUser                         thrpt       3   5.657 ± 1.132  ops/ms
ClientPb.listUser                        thrpt       3   4.630 ± 2.725  ops/ms
ClientPb.createUser                       avgt       3   5.923 ± 1.463   ms/op
ClientPb.existUser                        avgt       3   5.457 ± 2.140   ms/op
ClientPb.getUser                          avgt       3   6.061 ± 4.345   ms/op
ClientPb.listUser                         avgt       3   6.748 ± 1.933   ms/op
ClientPb.createUser                     sample  163840   5.860 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.241           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.332           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.323           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.502           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.906           ms/op
ClientPb.createUser:createUser·p0.9999  sample          43.909           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.958           ms/op
ClientPb.existUser                      sample  171243   5.607 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.943           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.471           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.583           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.775           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.996           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.504           ms/op
ClientPb.getUser                        sample  170822   5.619 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.866           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.250           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          29.235           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.324           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.994           ms/op
ClientPb.listUser                       sample  137060   6.999 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.220           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.431           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.191           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.699           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.097           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.603           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.288           ms/op
