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
# Warmup Iteration   1: 1.036 ops/ms
# Warmup Iteration   2: 2.262 ops/ms
# Warmup Iteration   3: 4.976 ops/ms
Iteration   1: 5.445 ops/ms
Iteration   2: 5.768 ops/ms
Iteration   3: 5.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.631 ±(99.9%) 3.053 ops/ms [Average]
  (min, avg, max) = (5.445, 5.631, 5.768), stdev = 0.167
  CI (99.9%): [2.579, 8.684] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.688 ops/ms
# Warmup Iteration   2: 4.922 ops/ms
# Warmup Iteration   3: 6.040 ops/ms
Iteration   1: 6.012 ops/ms
Iteration   2: 5.972 ops/ms
Iteration   3: 6.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.020 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (5.972, 6.020, 6.077), stdev = 0.053
  CI (99.9%): [5.049, 6.991] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 4.388 ops/ms
# Warmup Iteration   3: 5.788 ops/ms
Iteration   1: 5.721 ops/ms
Iteration   2: 5.855 ops/ms
Iteration   3: 5.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.792 ±(99.9%) 1.228 ops/ms [Average]
  (min, avg, max) = (5.721, 5.792, 5.855), stdev = 0.067
  CI (99.9%): [4.564, 7.020] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.710 ops/ms
# Warmup Iteration   2: 4.143 ops/ms
# Warmup Iteration   3: 4.812 ops/ms
Iteration   1: 4.683 ops/ms
Iteration   2: 4.901 ops/ms
Iteration   3: 4.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.822 ±(99.9%) 2.208 ops/ms [Average]
  (min, avg, max) = (4.683, 4.822, 4.901), stdev = 0.121
  CI (99.9%): [2.614, 7.030] (assumes normal distribution)


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
# Warmup Iteration   1: 17.383 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.393 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.735 ±(99.9%) 0.012 ms/op
Iteration   1: 5.621 ±(99.9%) 0.011 ms/op
Iteration   2: 5.488 ±(99.9%) 0.020 ms/op
Iteration   3: 5.520 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.543 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (5.488, 5.543, 5.621), stdev = 0.069
  CI (99.9%): [4.276, 6.810] (assumes normal distribution)


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
# Warmup Iteration   1: 16.370 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.583 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.443 ±(99.9%) 0.013 ms/op
Iteration   1: 5.071 ±(99.9%) 0.021 ms/op
Iteration   2: 5.113 ±(99.9%) 0.018 ms/op
Iteration   3: 5.225 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.136 ±(99.9%) 1.459 ms/op [Average]
  (min, avg, max) = (5.071, 5.136, 5.225), stdev = 0.080
  CI (99.9%): [3.678, 6.595] (assumes normal distribution)


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
# Warmup Iteration   1: 16.893 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.043 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.539 ±(99.9%) 0.011 ms/op
Iteration   1: 5.600 ±(99.9%) 0.008 ms/op
Iteration   2: 5.496 ±(99.9%) 0.014 ms/op
Iteration   3: 5.696 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.597 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (5.496, 5.597, 5.696), stdev = 0.100
  CI (99.9%): [3.777, 7.417] (assumes normal distribution)


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
# Warmup Iteration   1: 20.273 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 9.140 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.802 ±(99.9%) 0.017 ms/op
Iteration   1: 6.439 ±(99.9%) 0.026 ms/op
Iteration   2: 6.571 ±(99.9%) 0.017 ms/op
Iteration   3: 6.302 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.437 ±(99.9%) 2.460 ms/op [Average]
  (min, avg, max) = (6.302, 6.437, 6.571), stdev = 0.135
  CI (99.9%): [3.977, 8.897] (assumes normal distribution)


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
# Warmup Iteration   1: 19.227 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.192 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.291 ±(99.9%) 0.032 ms/op
Iteration   1: 5.740 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.478 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   7.324 ms/op
                 createUser·p0.95:   8.421 ms/op
                 createUser·p0.99:   11.223 ms/op
                 createUser·p0.999:  22.850 ms/op
                 createUser·p0.9999: 26.617 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   2: 5.583 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.906 ms/op
                 createUser·p0.95:   8.086 ms/op
                 createUser·p0.99:   11.682 ms/op
                 createUser·p0.999:  23.996 ms/op
                 createUser·p0.9999: 38.553 ms/op
                 createUser·p1.00:   39.387 ms/op

Iteration   3: 5.633 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.853 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   7.881 ms/op
                 createUser·p0.99:   10.109 ms/op
                 createUser·p0.999:  14.104 ms/op
                 createUser·p0.9999: 30.210 ms/op
                 createUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169642
  mean =      5.652 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 55196 
    [ 5.000,  7.500) = 101952 
    [ 7.500, 10.000) = 9891 
    [10.000, 12.500) = 1654 
    [12.500, 15.000) = 449 
    [15.000, 17.500) = 285 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.094 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     18.460 ms/op
     p(99.9900) =     37.882 ms/op
     p(99.9990) =     39.296 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


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
# Warmup Iteration   1: 17.625 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.346 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.354 ±(99.9%) 0.020 ms/op
Iteration   1: 5.475 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.322 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.816 ms/op
                 existUser·p0.95:   7.832 ms/op
                 existUser·p0.99:   10.797 ms/op
                 existUser·p0.999:  22.405 ms/op
                 existUser·p0.9999: 28.344 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 5.449 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.863 ms/op
                 existUser·p0.95:   7.859 ms/op
                 existUser·p0.99:   10.764 ms/op
                 existUser·p0.999:  16.196 ms/op
                 existUser·p0.9999: 30.588 ms/op
                 existUser·p1.00:   32.244 ms/op

Iteration   3: 5.586 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   7.307 ms/op
                 existUser·p0.95:   8.471 ms/op
                 existUser·p0.99:   11.272 ms/op
                 existUser·p0.999:  31.940 ms/op
                 existUser·p0.9999: 41.801 ms/op
                 existUser·p1.00:   43.123 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174314
  mean =      5.503 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 72248 
    [ 5.000, 10.000) = 99226 
    [10.000, 15.000) = 2405 
    [15.000, 20.000) = 256 
    [20.000, 25.000) = 22 
    [25.000, 30.000) = 80 
    [30.000, 35.000) = 44 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     38.348 ms/op
     p(99.9990) =     42.538 ms/op
     p(99.9999) =     43.123 ms/op
    p(100.0000) =     43.123 ms/op


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
# Warmup Iteration   1: 17.595 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 7.250 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.539 ±(99.9%) 0.021 ms/op
Iteration   1: 5.470 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.474 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   7.479 ms/op
                 getUser·p0.99:   9.929 ms/op
                 getUser·p0.999:  23.629 ms/op
                 getUser·p0.9999: 32.493 ms/op
                 getUser·p1.00:   34.341 ms/op

Iteration   2: 5.675 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.143 ms/op
                 getUser·p0.95:   8.782 ms/op
                 getUser·p0.99:   12.616 ms/op
                 getUser·p0.999:  26.049 ms/op
                 getUser·p0.9999: 37.648 ms/op
                 getUser·p1.00:   44.892 ms/op

Iteration   3: 5.387 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.519 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   7.160 ms/op
                 getUser·p0.99:   9.273 ms/op
                 getUser·p0.999:  28.529 ms/op
                 getUser·p0.9999: 32.508 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174142
  mean =      5.508 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 66685 
    [ 5.000, 10.000) = 105144 
    [10.000, 15.000) = 1999 
    [15.000, 20.000) = 100 
    [20.000, 25.000) = 48 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 98 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     24.735 ms/op
     p(99.9900) =     33.593 ms/op
     p(99.9990) =     40.325 ms/op
     p(99.9999) =     44.892 ms/op
    p(100.0000) =     44.892 ms/op


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
# Warmup Iteration   1: 18.310 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 8.290 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.538 ±(99.9%) 0.027 ms/op
Iteration   1: 6.366 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   6.062 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  26.960 ms/op
                 listUser·p0.9999: 30.207 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 6.463 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   8.940 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  30.694 ms/op
                 listUser·p0.9999: 36.916 ms/op
                 listUser·p1.00:   41.484 ms/op

Iteration   3: 6.375 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   7.759 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  24.122 ms/op
                 listUser·p0.9999: 29.425 ms/op
                 listUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149830
  mean =      6.401 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6806 
    [ 5.000, 10.000) = 139301 
    [10.000, 15.000) = 3252 
    [15.000, 20.000) = 194 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 147 
    [30.000, 35.000) = 54 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      6.078 ms/op
     p(90.0000) =      7.799 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     27.034 ms/op
     p(99.9900) =     35.588 ms/op
     p(99.9990) =     40.374 ms/op
     p(99.9999) =     41.484 ms/op
    p(100.0000) =     41.484 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.631 ± 3.053  ops/ms
ClientPb.existUser                       thrpt       3   6.020 ± 0.971  ops/ms
ClientPb.getUser                         thrpt       3   5.792 ± 1.228  ops/ms
ClientPb.listUser                        thrpt       3   4.822 ± 2.208  ops/ms
ClientPb.createUser                       avgt       3   5.543 ± 1.267   ms/op
ClientPb.existUser                        avgt       3   5.136 ± 1.459   ms/op
ClientPb.getUser                          avgt       3   5.597 ± 1.820   ms/op
ClientPb.listUser                         avgt       3   6.437 ± 2.460   ms/op
ClientPb.createUser                     sample  169642   5.652 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.853           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.094           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.135           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.010           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.460           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.882           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.387           ms/op
ClientPb.existUser                      sample  174314   5.503 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.737           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.988           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.077           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.010           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.808           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.348           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.123           ms/op
ClientPb.getUser                        sample  174142   5.508 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.727           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.210           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.742           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.797           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.735           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.593           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.892           ms/op
ClientPb.listUser                       sample  149830   6.401 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.142           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.078           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.799           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.698           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.034           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.588           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.484           ms/op
