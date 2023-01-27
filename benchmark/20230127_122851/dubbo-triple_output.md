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
# Warmup Iteration   1: 1.804 ops/ms
# Warmup Iteration   2: 4.021 ops/ms
# Warmup Iteration   3: 7.490 ops/ms
Iteration   1: 7.751 ops/ms
Iteration   2: 8.008 ops/ms
Iteration   3: 8.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.012 ±(99.9%) 4.811 ops/ms [Average]
  (min, avg, max) = (7.751, 8.012, 8.278), stdev = 0.264
  CI (99.9%): [3.201, 12.824] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.404 ops/ms
# Warmup Iteration   2: 7.456 ops/ms
# Warmup Iteration   3: 8.522 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 8.966 ops/ms
Iteration   3: 9.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.878 ±(99.9%) 4.785 ops/ms [Average]
  (min, avg, max) = (8.583, 8.878, 9.085), stdev = 0.262
  CI (99.9%): [4.093, 13.663] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.290 ops/ms
# Warmup Iteration   2: 7.015 ops/ms
# Warmup Iteration   3: 7.639 ops/ms
Iteration   1: 8.022 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.023 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (7.886, 8.023, 8.161), stdev = 0.138
  CI (99.9%): [5.509, 10.537] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.219 ops/ms
# Warmup Iteration   2: 6.083 ops/ms
# Warmup Iteration   3: 6.873 ops/ms
Iteration   1: 6.975 ops/ms
Iteration   2: 7.168 ops/ms
Iteration   3: 6.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.044 ±(99.9%) 1.953 ops/ms [Average]
  (min, avg, max) = (6.975, 7.044, 7.168), stdev = 0.107
  CI (99.9%): [5.091, 8.997] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.148 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.006 ms/op
Iteration   1: 3.857 ±(99.9%) 0.004 ms/op
Iteration   2: 3.757 ±(99.9%) 0.008 ms/op
Iteration   3: 3.876 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.830 ±(99.9%) 1.172 ms/op [Average]
  (min, avg, max) = (3.757, 3.830, 3.876), stdev = 0.064
  CI (99.9%): [2.658, 5.002] (assumes normal distribution)


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
# Warmup Iteration   1: 10.551 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.006 ms/op
Iteration   1: 3.782 ±(99.9%) 0.010 ms/op
Iteration   2: 3.653 ±(99.9%) 0.003 ms/op
Iteration   3: 3.547 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.661 ±(99.9%) 2.151 ms/op [Average]
  (min, avg, max) = (3.547, 3.661, 3.782), stdev = 0.118
  CI (99.9%): [1.509, 5.812] (assumes normal distribution)


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
# Warmup Iteration   1: 12.346 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.006 ms/op
Iteration   1: 3.795 ±(99.9%) 0.005 ms/op
Iteration   2: 3.801 ±(99.9%) 0.010 ms/op
Iteration   3: 3.827 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.808 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (3.795, 3.808, 3.827), stdev = 0.017
  CI (99.9%): [3.494, 4.121] (assumes normal distribution)


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
# Warmup Iteration   1: 12.174 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.210 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.622 ±(99.9%) 0.005 ms/op
Iteration   1: 4.334 ±(99.9%) 0.016 ms/op
Iteration   2: 4.417 ±(99.9%) 0.007 ms/op
Iteration   3: 4.515 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.422 ±(99.9%) 1.660 ms/op [Average]
  (min, avg, max) = (4.334, 4.422, 4.515), stdev = 0.091
  CI (99.9%): [2.762, 6.082] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.194 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.547 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.017 ms/op
Iteration   1: 4.036 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  15.219 ms/op
                 createUser·p0.9999: 25.798 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 3.943 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.201 ms/op
                 createUser·p0.999:  25.592 ms/op
                 createUser·p0.9999: 32.571 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   3: 3.760 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  25.025 ms/op
                 createUser·p0.9999: 34.373 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245566
  mean =      3.910 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1061 
    [ 2.500,  5.000) = 230851 
    [ 5.000,  7.500) = 11831 
    [ 7.500, 10.000) = 1282 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     23.509 ms/op
     p(99.9900) =     33.274 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 10.508 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.010 ms/op
Iteration   1: 3.668 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 24.169 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   2: 3.632 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.825 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  24.050 ms/op
                 existUser·p0.9999: 31.824 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   3: 3.745 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  9.776 ms/op
                 existUser·p0.9999: 34.699 ms/op
                 existUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 260472
  mean =      3.681 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1365 
    [ 2.500,  5.000) = 251861 
    [ 5.000,  7.500) = 5878 
    [ 7.500, 10.000) = 961 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     12.889 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     35.399 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 12.127 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.639 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.013 ms/op
Iteration   1: 3.921 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   8.045 ms/op
                 getUser·p0.999:  22.436 ms/op
                 getUser·p0.9999: 25.324 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.865 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  11.734 ms/op
                 getUser·p0.9999: 26.581 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   3: 3.770 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  28.436 ms/op
                 getUser·p0.9999: 31.883 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 249013
  mean =      3.851 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183 
    [ 2.500,  5.000) = 238469 
    [ 5.000,  7.500) = 8630 
    [ 7.500, 10.000) = 1106 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.937 ms/op
     p(99.9000) =     22.314 ms/op
     p(99.9900) =     30.314 ms/op
     p(99.9990) =     32.081 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 14.591 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.498 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.853 ±(99.9%) 0.019 ms/op
Iteration   1: 4.525 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  24.904 ms/op
                 listUser·p0.9999: 31.060 ms/op
                 listUser·p1.00:   33.751 ms/op

Iteration   2: 4.427 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  16.640 ms/op
                 listUser·p0.9999: 20.147 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 4.620 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  16.445 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211869
  mean =      4.523 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 192689 
    [ 5.000,  7.500) = 15675 
    [ 7.500, 10.000) = 2295 
    [10.000, 12.500) = 612 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.792 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     29.551 ms/op
     p(99.9990) =     33.351 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.012 ± 4.811  ops/ms
ClientPb.existUser                       thrpt       3   8.878 ± 4.785  ops/ms
ClientPb.getUser                         thrpt       3   8.023 ± 2.514  ops/ms
ClientPb.listUser                        thrpt       3   7.044 ± 1.953  ops/ms
ClientPb.createUser                       avgt       3   3.830 ± 1.172   ms/op
ClientPb.existUser                        avgt       3   3.661 ± 2.151   ms/op
ClientPb.getUser                          avgt       3   3.808 ± 0.313   ms/op
ClientPb.listUser                         avgt       3   4.422 ± 1.660   ms/op
ClientPb.createUser                     sample  245566   3.910 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.530           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.509           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.274           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  260472   3.681 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.947           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.668           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.889           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.013           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.979           ms/op
ClientPb.getUser                        sample  249013   3.851 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.186           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.937           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.314           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.314           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.178           ms/op
ClientPb.listUser                       sample  211869   4.523 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.792           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.292           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.891           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.551           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.751           ms/op
