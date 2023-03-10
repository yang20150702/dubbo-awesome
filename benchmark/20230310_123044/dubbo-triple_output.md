# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.623 ops/ms
# Warmup Iteration   2: 3.926 ops/ms
# Warmup Iteration   3: 7.457 ops/ms
Iteration   1: 7.402 ops/ms
Iteration   2: 8.219 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.949 ±(99.9%) 8.632 ops/ms [Average]
  (min, avg, max) = (7.402, 7.949, 8.225), stdev = 0.473
  CI (99.9%): [≈ 0, 16.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.720 ops/ms
# Warmup Iteration   2: 6.244 ops/ms
# Warmup Iteration   3: 8.234 ops/ms
Iteration   1: 8.314 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.429 ±(99.9%) 2.410 ops/ms [Average]
  (min, avg, max) = (8.314, 8.429, 8.573), stdev = 0.132
  CI (99.9%): [6.018, 10.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.294 ops/ms
# Warmup Iteration   2: 6.433 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 8.359 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.324 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (8.300, 8.324, 8.359), stdev = 0.031
  CI (99.9%): [7.762, 8.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 5.780 ops/ms
# Warmup Iteration   3: 6.668 ops/ms
Iteration   1: 6.842 ops/ms
Iteration   2: 7.002 ops/ms
Iteration   3: 6.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.935 ±(99.9%) 1.512 ops/ms [Average]
  (min, avg, max) = (6.842, 6.935, 7.002), stdev = 0.083
  CI (99.9%): [5.423, 8.447] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.759 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.006 ms/op
Iteration   1: 4.037 ±(99.9%) 0.011 ms/op
Iteration   2: 4.046 ±(99.9%) 0.005 ms/op
Iteration   3: 3.910 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.998 ±(99.9%) 1.386 ms/op [Average]
  (min, avg, max) = (3.910, 3.998, 4.046), stdev = 0.076
  CI (99.9%): [2.612, 5.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.462 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.008 ms/op
Iteration   1: 3.749 ±(99.9%) 0.007 ms/op
Iteration   2: 3.851 ±(99.9%) 0.006 ms/op
Iteration   3: 3.758 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.786 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.749, 3.786, 3.851), stdev = 0.056
  CI (99.9%): [2.760, 4.812] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.577 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.008 ms/op
Iteration   1: 3.828 ±(99.9%) 0.009 ms/op
Iteration   2: 4.049 ±(99.9%) 0.010 ms/op
Iteration   3: 3.796 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.891 ±(99.9%) 2.514 ms/op [Average]
  (min, avg, max) = (3.796, 3.891, 4.049), stdev = 0.138
  CI (99.9%): [1.377, 6.406] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.769 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.454 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.011 ms/op
Iteration   1: 4.667 ±(99.9%) 0.011 ms/op
Iteration   2: 4.547 ±(99.9%) 0.017 ms/op
Iteration   3: 4.766 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.660 ±(99.9%) 1.996 ms/op [Average]
  (min, avg, max) = (4.547, 4.660, 4.766), stdev = 0.109
  CI (99.9%): [2.664, 6.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.041 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.403 ±(99.9%) 0.018 ms/op
Iteration   1: 3.991 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  11.633 ms/op
                 createUser·p0.9999: 24.444 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   2: 3.993 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.874 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   8.282 ms/op
                 createUser·p0.999:  23.757 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.919 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  26.398 ms/op
                 createUser·p0.9999: 30.397 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242028
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 401 
    [ 2.500,  5.000) = 228002 
    [ 5.000,  7.500) = 11230 
    [ 7.500, 10.000) = 1589 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     22.446 ms/op
     p(99.9900) =     28.764 ms/op
     p(99.9990) =     31.588 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.038 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.013 ms/op
Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  20.414 ms/op
                 existUser·p0.9999: 22.791 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 3.999 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   7.651 ms/op
                 existUser·p0.999:  13.925 ms/op
                 existUser·p0.9999: 24.347 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.861 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  13.274 ms/op
                 existUser·p0.9999: 26.598 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247697
  mean =      3.873 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 315 
    [ 2.500,  5.000) = 228929 
    [ 5.000,  7.500) = 16396 
    [ 7.500, 10.000) = 1536 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.046 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     27.135 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.306 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.013 ms/op
Iteration   1: 4.122 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  22.683 ms/op
                 getUser·p0.9999: 24.835 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.932 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  10.087 ms/op
                 getUser·p0.9999: 26.673 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.952 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.236 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  26.868 ms/op
                 getUser·p0.9999: 29.583 ms/op
                 getUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239943
  mean =      4.000 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 227042 
    [ 5.000,  7.500) = 9755 
    [ 7.500, 10.000) = 2292 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.959 ms/op
     p(99.9000) =     22.513 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     30.881 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.428 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.475 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.876 ±(99.9%) 0.020 ms/op
Iteration   1: 4.709 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  25.100 ms/op
                 listUser·p0.9999: 27.099 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   2: 4.618 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 21.520 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 4.572 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  17.599 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 207118
  mean =      4.632 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 176898 
    [ 5.000,  7.500) = 25985 
    [ 7.500, 10.000) = 3086 
    [10.000, 12.500) = 536 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     21.983 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.326 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.949 ± 8.632  ops/ms
ClientPb.existUser                       thrpt       3   8.429 ± 2.410  ops/ms
ClientPb.getUser                         thrpt       3   8.324 ± 0.562  ops/ms
ClientPb.listUser                        thrpt       3   6.935 ± 1.512  ops/ms
ClientPb.createUser                       avgt       3   3.998 ± 1.386   ms/op
ClientPb.existUser                        avgt       3   3.786 ± 1.026   ms/op
ClientPb.getUser                          avgt       3   3.891 ± 2.514   ms/op
ClientPb.listUser                         avgt       3   4.660 ± 1.996   ms/op
ClientPb.createUser                     sample  242028   3.967 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.536           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.128           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.471           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.446           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.764           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752           ms/op
ClientPb.existUser                      sample  247697   3.873 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.370           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.258           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.046           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.083           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.197           ms/op
ClientPb.getUser                        sample  239943   4.000 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.364           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.079           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.959           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.513           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.000           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  207118   4.632 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.327           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.983           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.509           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.722           ms/op
