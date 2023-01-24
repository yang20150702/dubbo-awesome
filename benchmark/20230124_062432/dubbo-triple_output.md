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
# Warmup Iteration   1: 1.722 ops/ms
# Warmup Iteration   2: 3.670 ops/ms
# Warmup Iteration   3: 7.432 ops/ms
Iteration   1: 8.047 ops/ms
Iteration   2: 8.691 ops/ms
Iteration   3: 8.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.382 ±(99.9%) 5.880 ops/ms [Average]
  (min, avg, max) = (8.047, 8.382, 8.691), stdev = 0.322
  CI (99.9%): [2.501, 14.262] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.378 ops/ms
# Warmup Iteration   2: 6.595 ops/ms
# Warmup Iteration   3: 8.235 ops/ms
Iteration   1: 8.543 ops/ms
Iteration   2: 8.507 ops/ms
Iteration   3: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.536 ±(99.9%) 0.476 ops/ms [Average]
  (min, avg, max) = (8.507, 8.536, 8.558), stdev = 0.026
  CI (99.9%): [8.061, 9.012] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.478 ops/ms
# Warmup Iteration   2: 7.133 ops/ms
# Warmup Iteration   3: 7.900 ops/ms
Iteration   1: 8.398 ops/ms
Iteration   2: 8.647 ops/ms
Iteration   3: 8.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.489 ±(99.9%) 2.500 ops/ms [Average]
  (min, avg, max) = (8.398, 8.489, 8.647), stdev = 0.137
  CI (99.9%): [5.989, 10.990] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.101 ops/ms
# Warmup Iteration   2: 6.306 ops/ms
# Warmup Iteration   3: 6.841 ops/ms
Iteration   1: 6.887 ops/ms
Iteration   2: 6.951 ops/ms
Iteration   3: 6.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.945 ±(99.9%) 1.002 ops/ms [Average]
  (min, avg, max) = (6.887, 6.945, 6.997), stdev = 0.055
  CI (99.9%): [5.943, 7.947] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.332 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.010 ms/op
Iteration   1: 4.003 ±(99.9%) 0.008 ms/op
Iteration   2: 3.872 ±(99.9%) 0.011 ms/op
Iteration   3: 3.913 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.930 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (3.872, 3.930, 4.003), stdev = 0.067
  CI (99.9%): [2.709, 5.150] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.770 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.008 ms/op
Iteration   1: 3.617 ±(99.9%) 0.008 ms/op
Iteration   2: 3.574 ±(99.9%) 0.006 ms/op
Iteration   3: 3.738 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.643 ±(99.9%) 1.549 ms/op [Average]
  (min, avg, max) = (3.574, 3.643, 3.738), stdev = 0.085
  CI (99.9%): [2.093, 5.192] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.737 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.008 ms/op
Iteration   1: 3.791 ±(99.9%) 0.007 ms/op
Iteration   2: 3.710 ±(99.9%) 0.010 ms/op
Iteration   3: 3.892 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.798 ±(99.9%) 1.663 ms/op [Average]
  (min, avg, max) = (3.710, 3.798, 3.892), stdev = 0.091
  CI (99.9%): [2.134, 5.461] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.157 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.594 ±(99.9%) 0.012 ms/op
Iteration   1: 4.606 ±(99.9%) 0.009 ms/op
Iteration   2: 4.439 ±(99.9%) 0.015 ms/op
Iteration   3: 4.636 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.560 ±(99.9%) 1.935 ms/op [Average]
  (min, avg, max) = (4.439, 4.560, 4.636), stdev = 0.106
  CI (99.9%): [2.625, 6.496] (assumes normal distribution)


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
# Warmup Iteration   1: 13.754 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.937 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.017 ms/op
Iteration   1: 3.758 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  8.564 ms/op
                 createUser·p0.9999: 27.476 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 3.859 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  24.877 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 3.723 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  28.410 ms/op
                 createUser·p0.9999: 43.608 ms/op
                 createUser·p1.00:   44.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 253794
  mean =      3.779 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 244996 
    [ 5.000, 10.000) = 8170 
    [10.000, 15.000) = 319 
    [15.000, 20.000) = 21 
    [20.000, 25.000) = 62 
    [25.000, 30.000) = 160 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 43 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     44.499 ms/op
     p(99.9999) =     44.499 ms/op
    p(100.0000) =     44.499 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.823 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.012 ms/op
Iteration   1: 3.757 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  12.299 ms/op
                 existUser·p0.9999: 28.049 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 3.670 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  23.162 ms/op
                 existUser·p0.9999: 26.228 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.729 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 27.605 ms/op
                 existUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 257994
  mean =      3.718 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1107 
    [ 2.500,  5.000) = 248231 
    [ 5.000,  7.500) = 7111 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 123 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     29.287 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 11.767 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.013 ms/op
Iteration   1: 3.824 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.964 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  22.880 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 3.621 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 26.908 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.640 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  25.105 ms/op
                 getUser·p0.9999: 27.754 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 259956
  mean =      3.693 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 299 
    [ 2.500,  5.000) = 252959 
    [ 5.000,  7.500) = 4973 
    [ 7.500, 10.000) = 1178 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 134 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     27.198 ms/op
     p(99.9990) =     28.161 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.578 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.182 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.017 ms/op
Iteration   1: 4.537 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  23.724 ms/op
                 listUser·p0.9999: 27.458 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   2: 4.438 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  16.317 ms/op
                 listUser·p0.9999: 18.927 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 4.573 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 26.248 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212499
  mean =      4.516 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 190367 
    [ 5.000,  7.500) = 17998 
    [ 7.500, 10.000) = 3134 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     18.596 ms/op
     p(99.9900) =     26.919 ms/op
     p(99.9990) =     27.849 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.382 ± 5.880  ops/ms
ClientPb.existUser                       thrpt       3   8.536 ± 0.476  ops/ms
ClientPb.getUser                         thrpt       3   8.489 ± 2.500  ops/ms
ClientPb.listUser                        thrpt       3   6.945 ± 1.002  ops/ms
ClientPb.createUser                       avgt       3   3.930 ± 1.221   ms/op
ClientPb.existUser                        avgt       3   3.643 ± 1.549   ms/op
ClientPb.getUser                          avgt       3   3.798 ± 1.663   ms/op
ClientPb.listUser                         avgt       3   4.560 ± 1.935   ms/op
ClientPb.createUser                     sample  253794   3.779 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.719           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.406           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.412           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.421           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.499           ms/op
ClientPb.existUser                      sample  257994   3.718 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.389           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.460           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.491           ms/op
ClientPb.getUser                        sample  259956   3.693 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.135           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.198           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.344           ms/op
ClientPb.listUser                       sample  212499   4.516 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.495           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.596           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.919           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.984           ms/op
