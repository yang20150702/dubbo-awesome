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
# Warmup Iteration   1: 1.147 ops/ms
# Warmup Iteration   2: 2.554 ops/ms
# Warmup Iteration   3: 5.127 ops/ms
Iteration   1: 5.762 ops/ms
Iteration   2: 5.721 ops/ms
Iteration   3: 5.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.816 ±(99.9%) 2.404 ops/ms [Average]
  (min, avg, max) = (5.721, 5.816, 5.967), stdev = 0.132
  CI (99.9%): [3.413, 8.220] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.717 ops/ms
# Warmup Iteration   2: 5.144 ops/ms
# Warmup Iteration   3: 5.631 ops/ms
Iteration   1: 5.671 ops/ms
Iteration   2: 5.611 ops/ms
Iteration   3: 5.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.746 ±(99.9%) 3.356 ops/ms [Average]
  (min, avg, max) = (5.611, 5.746, 5.956), stdev = 0.184
  CI (99.9%): [2.390, 9.102] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.501 ops/ms
# Warmup Iteration   2: 5.025 ops/ms
# Warmup Iteration   3: 5.654 ops/ms
Iteration   1: 5.745 ops/ms
Iteration   2: 5.877 ops/ms
Iteration   3: 5.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.752 ±(99.9%) 2.224 ops/ms [Average]
  (min, avg, max) = (5.633, 5.752, 5.877), stdev = 0.122
  CI (99.9%): [3.528, 7.976] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.470 ops/ms
# Warmup Iteration   2: 3.556 ops/ms
# Warmup Iteration   3: 4.124 ops/ms
Iteration   1: 4.667 ops/ms
Iteration   2: 4.621 ops/ms
Iteration   3: 4.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.638 ±(99.9%) 0.459 ops/ms [Average]
  (min, avg, max) = (4.621, 4.638, 4.667), stdev = 0.025
  CI (99.9%): [4.179, 5.098] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.133 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.896 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.014 ms/op
Iteration   1: 5.853 ±(99.9%) 0.013 ms/op
Iteration   2: 5.744 ±(99.9%) 0.014 ms/op
Iteration   3: 5.938 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.845 ±(99.9%) 1.774 ms/op [Average]
  (min, avg, max) = (5.744, 5.845, 5.938), stdev = 0.097
  CI (99.9%): [4.071, 7.619] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.497 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.952 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.388 ±(99.9%) 0.013 ms/op
Iteration   1: 5.385 ±(99.9%) 0.012 ms/op
Iteration   2: 5.451 ±(99.9%) 0.021 ms/op
Iteration   3: 5.484 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.440 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (5.385, 5.440, 5.484), stdev = 0.051
  CI (99.9%): [4.517, 6.363] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.472 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 7.007 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.780 ±(99.9%) 0.015 ms/op
Iteration   1: 5.763 ±(99.9%) 0.011 ms/op
Iteration   2: 5.943 ±(99.9%) 0.010 ms/op
Iteration   3: 6.049 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.918 ±(99.9%) 2.640 ms/op [Average]
  (min, avg, max) = (5.763, 5.918, 6.049), stdev = 0.145
  CI (99.9%): [3.279, 8.558] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 23.559 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 10.404 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 7.960 ±(99.9%) 0.023 ms/op
Iteration   1: 7.329 ±(99.9%) 0.031 ms/op
Iteration   2: 7.277 ±(99.9%) 0.023 ms/op
Iteration   3: 6.985 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.197 ±(99.9%) 3.386 ms/op [Average]
  (min, avg, max) = (6.985, 7.197, 7.329), stdev = 0.186
  CI (99.9%): [3.811, 10.583] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.202 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 8.179 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.619 ±(99.9%) 0.034 ms/op
Iteration   1: 6.596 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   2.699 ms/op
                 createUser·p0.50:   5.964 ms/op
                 createUser·p0.90:   9.388 ms/op
                 createUser·p0.95:   11.076 ms/op
                 createUser·p0.99:   14.434 ms/op
                 createUser·p0.999:  22.411 ms/op
                 createUser·p0.9999: 27.366 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   2: 5.969 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.343 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   7.438 ms/op
                 createUser·p0.95:   8.864 ms/op
                 createUser·p0.99:   12.009 ms/op
                 createUser·p0.999:  28.830 ms/op
                 createUser·p0.9999: 32.637 ms/op
                 createUser·p1.00:   33.489 ms/op

Iteration   3: 5.985 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.888 ms/op
                 createUser·p0.50:   5.702 ms/op
                 createUser·p0.90:   7.315 ms/op
                 createUser·p0.95:   8.225 ms/op
                 createUser·p0.99:   10.584 ms/op
                 createUser·p0.999:  28.538 ms/op
                 createUser·p0.9999: 34.210 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 155637
  mean =      6.170 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 24834 
    [ 5.000,  7.500) = 111333 
    [ 7.500, 10.000) = 13313 
    [10.000, 12.500) = 4396 
    [12.500, 15.000) = 1140 
    [15.000, 17.500) = 317 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.343 ms/op
     p(50.0000) =      5.734 ms/op
     p(90.0000) =      7.930 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     24.043 ms/op
     p(99.9900) =     33.470 ms/op
     p(99.9990) =     34.748 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 17.314 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.945 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.288 ±(99.9%) 0.035 ms/op
Iteration   1: 5.845 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   2.097 ms/op
                 existUser·p0.50:   5.399 ms/op
                 existUser·p0.90:   7.660 ms/op
                 existUser·p0.95:   8.962 ms/op
                 existUser·p0.99:   12.517 ms/op
                 existUser·p0.999:  26.668 ms/op
                 existUser·p0.9999: 35.717 ms/op
                 existUser·p1.00:   35.914 ms/op

Iteration   2: 5.497 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.449 ms/op
                 existUser·p0.50:   5.226 ms/op
                 existUser·p0.90:   6.570 ms/op
                 existUser·p0.95:   7.512 ms/op
                 existUser·p0.99:   10.797 ms/op
                 existUser·p0.999:  26.297 ms/op
                 existUser·p0.9999: 30.003 ms/op
                 existUser·p1.00:   31.228 ms/op

Iteration   3: 5.499 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.290 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   7.635 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  17.296 ms/op
                 existUser·p0.9999: 33.147 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171008
  mean =      5.609 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 57436 
    [ 5.000,  7.500) = 101448 
    [ 7.500, 10.000) = 8887 
    [10.000, 12.500) = 2250 
    [12.500, 15.000) = 573 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      8.110 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 18.890 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 8.151 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.247 ±(99.9%) 0.027 ms/op
Iteration   1: 6.117 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.904 ms/op
                 getUser·p0.50:   5.636 ms/op
                 getUser·p0.90:   7.791 ms/op
                 getUser·p0.95:   9.454 ms/op
                 getUser·p0.99:   12.960 ms/op
                 getUser·p0.999:  24.874 ms/op
                 getUser·p0.9999: 44.171 ms/op
                 getUser·p1.00:   45.744 ms/op

Iteration   2: 5.871 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   5.612 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   7.791 ms/op
                 getUser·p0.99:   11.534 ms/op
                 getUser·p0.999:  20.795 ms/op
                 getUser·p0.9999: 33.939 ms/op
                 getUser·p1.00:   35.455 ms/op

Iteration   3: 5.631 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.376 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   8.020 ms/op
                 getUser·p0.99:   10.371 ms/op
                 getUser·p0.999:  29.704 ms/op
                 getUser·p0.9999: 42.554 ms/op
                 getUser·p1.00:   43.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163623
  mean =      5.866 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 34924 
    [ 5.000, 10.000) = 125042 
    [10.000, 15.000) = 3121 
    [15.000, 20.000) = 312 
    [20.000, 25.000) = 75 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 49 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     23.015 ms/op
     p(99.9900) =     42.926 ms/op
     p(99.9990) =     45.702 ms/op
     p(99.9999) =     45.744 ms/op
    p(100.0000) =     45.744 ms/op


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
# Warmup Iteration   1: 19.377 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 9.625 ±(99.9%) 0.078 ms/op
# Warmup Iteration   3: 7.220 ±(99.9%) 0.035 ms/op
Iteration   1: 6.707 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   7.979 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   13.287 ms/op
                 listUser·p0.999:  27.130 ms/op
                 listUser·p0.9999: 29.973 ms/op
                 listUser·p1.00:   30.540 ms/op

Iteration   2: 6.550 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  29.103 ms/op
                 listUser·p0.9999: 35.571 ms/op
                 listUser·p1.00:   38.732 ms/op

Iteration   3: 6.460 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.092 ms/op
                 listUser·p0.50:   6.210 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  28.508 ms/op
                 listUser·p0.9999: 33.568 ms/op
                 listUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146026
  mean =      6.571 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 3299 
    [ 5.000,  7.500) = 125511 
    [ 7.500, 10.000) = 12912 
    [10.000, 12.500) = 2979 
    [12.500, 15.000) = 767 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      6.267 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     28.081 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     38.641 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.816 ± 2.404  ops/ms
ClientPb.existUser                       thrpt       3   5.746 ± 3.356  ops/ms
ClientPb.getUser                         thrpt       3   5.752 ± 2.224  ops/ms
ClientPb.listUser                        thrpt       3   4.638 ± 0.459  ops/ms
ClientPb.createUser                       avgt       3   5.845 ± 1.774   ms/op
ClientPb.existUser                        avgt       3   5.440 ± 0.923   ms/op
ClientPb.getUser                          avgt       3   5.918 ± 2.640   ms/op
ClientPb.listUser                         avgt       3   7.197 ± 3.386   ms/op
ClientPb.createUser                     sample  155637   6.170 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.343           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.930           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.454           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.730           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.043           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.470           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.931           ms/op
ClientPb.existUser                      sample  171008   5.609 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.097           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.110           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.972           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.537           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.914           ms/op
ClientPb.getUser                        sample  163623   5.866 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.358           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.521           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.184           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.454           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.960           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.015           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.926           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.744           ms/op
ClientPb.listUser                       sample  146026   6.571 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.267           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.288           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.081           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.603           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.732           ms/op
