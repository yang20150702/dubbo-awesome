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
# Warmup Iteration   1: 1.115 ops/ms
# Warmup Iteration   2: 2.357 ops/ms
# Warmup Iteration   3: 5.243 ops/ms
Iteration   1: 5.634 ops/ms
Iteration   2: 5.495 ops/ms
Iteration   3: 5.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.568 ±(99.9%) 1.274 ops/ms [Average]
  (min, avg, max) = (5.495, 5.568, 5.634), stdev = 0.070
  CI (99.9%): [4.294, 6.841] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.775 ops/ms
# Warmup Iteration   2: 4.373 ops/ms
# Warmup Iteration   3: 5.949 ops/ms
Iteration   1: 5.996 ops/ms
Iteration   2: 5.918 ops/ms
Iteration   3: 5.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.910 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (5.816, 5.910, 5.996), stdev = 0.090
  CI (99.9%): [4.267, 7.554] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.500 ops/ms
# Warmup Iteration   2: 4.111 ops/ms
# Warmup Iteration   3: 5.421 ops/ms
Iteration   1: 5.647 ops/ms
Iteration   2: 5.635 ops/ms
Iteration   3: 5.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.706 ±(99.9%) 2.029 ops/ms [Average]
  (min, avg, max) = (5.635, 5.706, 5.834), stdev = 0.111
  CI (99.9%): [3.676, 7.735] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 3.821 ops/ms
# Warmup Iteration   3: 4.636 ops/ms
Iteration   1: 4.677 ops/ms
Iteration   2: 4.931 ops/ms
Iteration   3: 4.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.684 ±(99.9%) 4.438 ops/ms [Average]
  (min, avg, max) = (4.444, 4.684, 4.931), stdev = 0.243
  CI (99.9%): [0.246, 9.122] (assumes normal distribution)


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
# Warmup Iteration   1: 20.023 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.281 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.867 ±(99.9%) 0.007 ms/op
Iteration   1: 5.890 ±(99.9%) 0.005 ms/op
Iteration   2: 5.477 ±(99.9%) 0.018 ms/op
Iteration   3: 5.467 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.611 ±(99.9%) 4.406 ms/op [Average]
  (min, avg, max) = (5.467, 5.611, 5.890), stdev = 0.242
  CI (99.9%): [1.205, 10.018] (assumes normal distribution)


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
# Warmup Iteration   1: 17.040 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.657 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.740 ±(99.9%) 0.007 ms/op
Iteration   1: 5.609 ±(99.9%) 0.008 ms/op
Iteration   2: 5.280 ±(99.9%) 0.013 ms/op
Iteration   3: 5.305 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.398 ±(99.9%) 3.342 ms/op [Average]
  (min, avg, max) = (5.280, 5.398, 5.609), stdev = 0.183
  CI (99.9%): [2.056, 8.740] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.637 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.770 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.486 ±(99.9%) 0.016 ms/op
Iteration   1: 5.429 ±(99.9%) 0.012 ms/op
Iteration   2: 5.707 ±(99.9%) 0.007 ms/op
Iteration   3: 5.574 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.570 ±(99.9%) 2.542 ms/op [Average]
  (min, avg, max) = (5.429, 5.570, 5.707), stdev = 0.139
  CI (99.9%): [3.027, 8.112] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.973 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 8.685 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.812 ±(99.9%) 0.014 ms/op
Iteration   1: 6.576 ±(99.9%) 0.010 ms/op
Iteration   2: 6.470 ±(99.9%) 0.017 ms/op
Iteration   3: 6.662 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.569 ±(99.9%) 1.752 ms/op [Average]
  (min, avg, max) = (6.470, 6.569, 6.662), stdev = 0.096
  CI (99.9%): [4.818, 8.321] (assumes normal distribution)


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
# Warmup Iteration   1: 18.793 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 7.080 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.549 ±(99.9%) 0.032 ms/op
Iteration   1: 5.939 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   5.644 ms/op
                 createUser·p0.90:   7.381 ms/op
                 createUser·p0.95:   8.167 ms/op
                 createUser·p0.99:   11.174 ms/op
                 createUser·p0.999:  17.044 ms/op
                 createUser·p0.9999: 28.594 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   2: 6.383 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   2.589 ms/op
                 createUser·p0.50:   5.849 ms/op
                 createUser·p0.90:   8.585 ms/op
                 createUser·p0.95:   9.994 ms/op
                 createUser·p0.99:   13.484 ms/op
                 createUser·p0.999:  27.585 ms/op
                 createUser·p0.9999: 31.981 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 5.755 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.114 ms/op
                 createUser·p0.50:   5.448 ms/op
                 createUser·p0.90:   7.077 ms/op
                 createUser·p0.95:   8.094 ms/op
                 createUser·p0.99:   11.026 ms/op
                 createUser·p0.999:  30.019 ms/op
                 createUser·p0.9999: 35.746 ms/op
                 createUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 159483
  mean =      6.014 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 31715 
    [ 5.000,  7.500) = 110240 
    [ 7.500, 10.000) = 13240 
    [10.000, 12.500) = 2859 
    [12.500, 15.000) = 965 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.643 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     25.468 ms/op
     p(99.9900) =     33.817 ms/op
     p(99.9990) =     37.189 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 18.334 ±(99.9%) 0.333 ms/op
# Warmup Iteration   2: 7.759 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 5.717 ±(99.9%) 0.023 ms/op
Iteration   1: 5.947 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   5.472 ms/op
                 existUser·p0.90:   7.987 ms/op
                 existUser·p0.95:   9.519 ms/op
                 existUser·p0.99:   12.550 ms/op
                 existUser·p0.999:  26.259 ms/op
                 existUser·p0.9999: 29.469 ms/op
                 existUser·p1.00:   31.293 ms/op

Iteration   2: 5.663 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   7.365 ms/op
                 existUser·p0.95:   8.323 ms/op
                 existUser·p0.99:   11.960 ms/op
                 existUser·p0.999:  27.656 ms/op
                 existUser·p0.9999: 34.888 ms/op
                 existUser·p1.00:   35.127 ms/op

Iteration   3: 5.902 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.441 ms/op
                 existUser·p0.50:   5.571 ms/op
                 existUser·p0.90:   7.447 ms/op
                 existUser·p0.95:   8.487 ms/op
                 existUser·p0.99:   11.026 ms/op
                 existUser·p0.999:  18.743 ms/op
                 existUser·p0.9999: 36.766 ms/op
                 existUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 164548
  mean =      5.834 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 48682 
    [ 5.000,  7.500) = 99325 
    [ 7.500, 10.000) = 12441 
    [10.000, 12.500) = 2726 
    [12.500, 15.000) = 695 
    [15.000, 17.500) = 341 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.504 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     11.944 ms/op
     p(99.9000) =     23.378 ms/op
     p(99.9900) =     35.330 ms/op
     p(99.9990) =     37.051 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 19.895 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 8.514 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 5.594 ±(99.9%) 0.020 ms/op
Iteration   1: 5.824 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.433 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   7.389 ms/op
                 getUser·p0.95:   8.913 ms/op
                 getUser·p0.99:   14.238 ms/op
                 getUser·p0.999:  22.807 ms/op
                 getUser·p0.9999: 31.146 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   2: 5.813 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.789 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   6.996 ms/op
                 getUser·p0.95:   8.298 ms/op
                 getUser·p0.99:   11.640 ms/op
                 getUser·p0.999:  28.865 ms/op
                 getUser·p0.9999: 33.781 ms/op
                 getUser·p1.00:   35.717 ms/op

Iteration   3: 5.556 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.520 ms/op
                 getUser·p0.99:   10.256 ms/op
                 getUser·p0.999:  28.609 ms/op
                 getUser·p0.9999: 33.128 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167779
  mean =      5.728 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 47174 
    [ 5.000,  7.500) = 108597 
    [ 7.500, 10.000) = 8242 
    [10.000, 12.500) = 2109 
    [12.500, 15.000) = 916 
    [15.000, 17.500) = 438 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     12.435 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     33.340 ms/op
     p(99.9990) =     35.406 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 18.537 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 7.641 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.680 ±(99.9%) 0.029 ms/op
Iteration   1: 6.633 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.021 ms/op
                 listUser·p0.50:   6.300 ms/op
                 listUser·p0.90:   7.971 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   12.959 ms/op
                 listUser·p0.999:  26.168 ms/op
                 listUser·p0.9999: 29.071 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   2: 6.508 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.913 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  26.870 ms/op
                 listUser·p0.9999: 30.903 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   3: 6.685 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.011 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.176 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   12.796 ms/op
                 listUser·p0.999:  25.007 ms/op
                 listUser·p0.9999: 29.138 ms/op
                 listUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145242
  mean =      6.608 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 3871 
    [ 5.000,  7.500) = 120394 
    [ 7.500, 10.000) = 15590 
    [10.000, 12.500) = 4025 
    [12.500, 15.000) = 690 
    [15.000, 17.500) = 299 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 133 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      6.234 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =      9.355 ms/op
     p(99.0000) =     12.386 ms/op
     p(99.9000) =     26.338 ms/op
     p(99.9900) =     30.273 ms/op
     p(99.9990) =     31.780 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.568 ± 1.274  ops/ms
ClientPb.existUser                       thrpt       3   5.910 ± 1.643  ops/ms
ClientPb.getUser                         thrpt       3   5.706 ± 2.029  ops/ms
ClientPb.listUser                        thrpt       3   4.684 ± 4.438  ops/ms
ClientPb.createUser                       avgt       3   5.611 ± 4.406   ms/op
ClientPb.existUser                        avgt       3   5.398 ± 3.342   ms/op
ClientPb.getUser                          avgt       3   5.570 ± 2.542   ms/op
ClientPb.listUser                         avgt       3   6.569 ± 1.752   ms/op
ClientPb.createUser                     sample  159483   6.014 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.643           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.831           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.141           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.468           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.817           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.618           ms/op
ClientPb.existUser                      sample  164548   5.834 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.540           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.504           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.815           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.944           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.378           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.330           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.093           ms/op
ClientPb.getUser                        sample  167779   5.728 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.950           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.366           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.249           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.435           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.839           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.340           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.717           ms/op
ClientPb.listUser                       sample  145242   6.608 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.021           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.234           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.355           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.386           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.338           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.273           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.047           ms/op
