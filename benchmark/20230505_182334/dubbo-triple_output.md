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
# Warmup Iteration   1: 1.039 ops/ms
# Warmup Iteration   2: 2.264 ops/ms
# Warmup Iteration   3: 4.714 ops/ms
Iteration   1: 5.122 ops/ms
Iteration   2: 5.425 ops/ms
Iteration   3: 5.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.361 ±(99.9%) 3.914 ops/ms [Average]
  (min, avg, max) = (5.122, 5.361, 5.536), stdev = 0.215
  CI (99.9%): [1.447, 9.275] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.439 ops/ms
# Warmup Iteration   2: 4.613 ops/ms
# Warmup Iteration   3: 5.606 ops/ms
Iteration   1: 5.984 ops/ms
Iteration   2: 5.904 ops/ms
Iteration   3: 6.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.000 ±(99.9%) 1.931 ops/ms [Average]
  (min, avg, max) = (5.904, 6.000, 6.114), stdev = 0.106
  CI (99.9%): [4.069, 7.932] (assumes normal distribution)


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
# Warmup Iteration   1: 1.306 ops/ms
# Warmup Iteration   2: 4.074 ops/ms
# Warmup Iteration   3: 5.360 ops/ms
Iteration   1: 5.482 ops/ms
Iteration   2: 5.652 ops/ms
Iteration   3: 5.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.518 ±(99.9%) 2.191 ops/ms [Average]
  (min, avg, max) = (5.421, 5.518, 5.652), stdev = 0.120
  CI (99.9%): [3.327, 7.710] (assumes normal distribution)


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
# Warmup Iteration   1: 1.351 ops/ms
# Warmup Iteration   2: 3.803 ops/ms
# Warmup Iteration   3: 4.745 ops/ms
Iteration   1: 4.669 ops/ms
Iteration   2: 4.819 ops/ms
Iteration   3: 4.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.752 ±(99.9%) 1.388 ops/ms [Average]
  (min, avg, max) = (4.669, 4.752, 4.819), stdev = 0.076
  CI (99.9%): [3.365, 6.140] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 21.945 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 7.423 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.873 ±(99.9%) 0.017 ms/op
Iteration   1: 5.722 ±(99.9%) 0.013 ms/op
Iteration   2: 5.778 ±(99.9%) 0.017 ms/op
Iteration   3: 5.605 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.702 ±(99.9%) 1.609 ms/op [Average]
  (min, avg, max) = (5.605, 5.702, 5.778), stdev = 0.088
  CI (99.9%): [4.093, 7.311] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.641 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 7.401 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.522 ±(99.9%) 0.011 ms/op
Iteration   1: 5.470 ±(99.9%) 0.015 ms/op
Iteration   2: 5.581 ±(99.9%) 0.016 ms/op
Iteration   3: 5.608 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.553 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (5.470, 5.553, 5.608), stdev = 0.073
  CI (99.9%): [4.216, 6.891] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.400 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.892 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.666 ±(99.9%) 0.014 ms/op
Iteration   1: 5.949 ±(99.9%) 0.015 ms/op
Iteration   2: 5.772 ±(99.9%) 0.013 ms/op
Iteration   3: 5.667 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.796 ±(99.9%) 2.598 ms/op [Average]
  (min, avg, max) = (5.667, 5.796, 5.949), stdev = 0.142
  CI (99.9%): [3.197, 8.394] (assumes normal distribution)


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
# Warmup Iteration   1: 21.384 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 8.807 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 7.050 ±(99.9%) 0.017 ms/op
Iteration   1: 6.682 ±(99.9%) 0.020 ms/op
Iteration   2: 6.718 ±(99.9%) 0.014 ms/op
Iteration   3: 6.562 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.654 ±(99.9%) 1.497 ms/op [Average]
  (min, avg, max) = (6.562, 6.654, 6.718), stdev = 0.082
  CI (99.9%): [5.157, 8.151] (assumes normal distribution)


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
# Warmup Iteration   1: 19.202 ±(99.9%) 0.390 ms/op
# Warmup Iteration   2: 7.681 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.060 ±(99.9%) 0.028 ms/op
Iteration   1: 5.738 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.183 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   7.217 ms/op
                 createUser·p0.95:   8.282 ms/op
                 createUser·p0.99:   10.633 ms/op
                 createUser·p0.999:  22.950 ms/op
                 createUser·p0.9999: 25.914 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   2: 5.780 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.422 ms/op
                 createUser·p0.95:   8.634 ms/op
                 createUser·p0.99:   11.400 ms/op
                 createUser·p0.999:  25.428 ms/op
                 createUser·p0.9999: 30.767 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   3: 5.572 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.548 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   10.475 ms/op
                 createUser·p0.999:  19.121 ms/op
                 createUser·p0.9999: 29.664 ms/op
                 createUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168500
  mean =      5.695 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 47986 
    [ 5.000,  7.500) = 107540 
    [ 7.500, 10.000) = 10214 
    [10.000, 12.500) = 2062 
    [12.500, 15.000) = 421 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.183 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.127 ms/op
     p(95.0000) =      8.192 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     23.036 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     30.985 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.186 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 7.122 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.504 ±(99.9%) 0.019 ms/op
Iteration   1: 5.500 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.548 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.914 ms/op
                 existUser·p0.95:   8.176 ms/op
                 existUser·p0.99:   11.108 ms/op
                 existUser·p0.999:  16.646 ms/op
                 existUser·p0.9999: 27.198 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   2: 5.234 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.380 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.275 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   10.336 ms/op
                 existUser·p0.999:  27.001 ms/op
                 existUser·p0.9999: 31.293 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   3: 5.525 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.310 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   7.045 ms/op
                 existUser·p0.95:   8.178 ms/op
                 existUser·p0.99:   10.732 ms/op
                 existUser·p0.999:  27.861 ms/op
                 existUser·p0.9999: 32.965 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177102
  mean =      5.416 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 82165 
    [ 5.000,  7.500) = 83540 
    [ 7.500, 10.000) = 8717 
    [10.000, 12.500) = 1839 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.758 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     32.127 ms/op
     p(99.9990) =     33.508 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.428 ±(99.9%) 0.412 ms/op
# Warmup Iteration   2: 7.318 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.039 ±(99.9%) 0.028 ms/op
Iteration   1: 5.906 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.703 ms/op
                 getUser·p0.50:   5.579 ms/op
                 getUser·p0.90:   7.193 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   11.878 ms/op
                 getUser·p0.999:  16.394 ms/op
                 getUser·p0.9999: 28.705 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   2: 6.008 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   5.554 ms/op
                 getUser·p0.90:   7.528 ms/op
                 getUser·p0.95:   9.372 ms/op
                 getUser·p0.99:   13.803 ms/op
                 getUser·p0.999:  28.008 ms/op
                 getUser·p0.9999: 31.905 ms/op
                 getUser·p1.00:   32.866 ms/op

Iteration   3: 5.735 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.298 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   6.914 ms/op
                 getUser·p0.95:   7.782 ms/op
                 getUser·p0.99:   10.276 ms/op
                 getUser·p0.999:  29.367 ms/op
                 getUser·p0.9999: 34.110 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163221
  mean =      5.881 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 31640 
    [ 5.000,  7.500) = 118170 
    [ 7.500, 10.000) = 9528 
    [10.000, 12.500) = 2597 
    [12.500, 15.000) = 661 
    [15.000, 17.500) = 323 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     11.813 ms/op
     p(99.9000) =     22.439 ms/op
     p(99.9900) =     32.561 ms/op
     p(99.9990) =     34.927 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 23.354 ±(99.9%) 0.388 ms/op
# Warmup Iteration   2: 9.094 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 7.167 ±(99.9%) 0.034 ms/op
Iteration   1: 6.951 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.367 ms/op
                 listUser·p0.50:   6.554 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   13.903 ms/op
                 listUser·p0.999:  26.601 ms/op
                 listUser·p0.9999: 28.927 ms/op
                 listUser·p1.00:   29.295 ms/op

Iteration   2: 6.578 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.732 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   12.763 ms/op
                 listUser·p0.999:  29.615 ms/op
                 listUser·p0.9999: 32.847 ms/op
                 listUser·p1.00:   33.423 ms/op

Iteration   3: 6.822 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.092 ms/op
                 listUser·p0.50:   6.488 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.372 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  29.580 ms/op
                 listUser·p0.9999: 36.176 ms/op
                 listUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141506
  mean =      6.780 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2673 
    [ 5.000,  7.500) = 116446 
    [ 7.500, 10.000) = 16175 
    [10.000, 12.500) = 4329 
    [12.500, 15.000) = 1188 
    [15.000, 17.500) = 344 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.732 ms/op
     p(50.0000) =      6.373 ms/op
     p(90.0000) =      8.225 ms/op
     p(95.0000) =      9.732 ms/op
     p(99.0000) =     13.238 ms/op
     p(99.9000) =     28.442 ms/op
     p(99.9900) =     35.052 ms/op
     p(99.9990) =     36.449 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.361 ± 3.914  ops/ms
ClientPb.existUser                       thrpt       3   6.000 ± 1.931  ops/ms
ClientPb.getUser                         thrpt       3   5.518 ± 2.191  ops/ms
ClientPb.listUser                        thrpt       3   4.752 ± 1.388  ops/ms
ClientPb.createUser                       avgt       3   5.702 ± 1.609   ms/op
ClientPb.existUser                        avgt       3   5.553 ± 1.337   ms/op
ClientPb.getUser                          avgt       3   5.796 ± 2.598   ms/op
ClientPb.listUser                         avgt       3   6.654 ± 1.497   ms/op
ClientPb.createUser                     sample  168500   5.695 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.183           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.127           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.192           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.764           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.036           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.753           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.097           ms/op
ClientPb.existUser                      sample  177102   5.416 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.310           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.063           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.758           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.954           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.715           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.940           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.127           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  163221   5.881 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.649           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.176           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.813           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.439           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.561           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.258           ms/op
ClientPb.listUser                       sample  141506   6.780 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.373           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.732           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.238           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.442           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.052           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.504           ms/op
