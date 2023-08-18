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
# Warmup Iteration   1: 1.643 ops/ms
# Warmup Iteration   2: 3.571 ops/ms
# Warmup Iteration   3: 6.633 ops/ms
Iteration   1: 7.540 ops/ms
Iteration   2: 7.906 ops/ms
Iteration   3: 7.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.777 ±(99.9%) 3.741 ops/ms [Average]
  (min, avg, max) = (7.540, 7.777, 7.906), stdev = 0.205
  CI (99.9%): [4.036, 11.518] (assumes normal distribution)


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
# Warmup Iteration   1: 2.222 ops/ms
# Warmup Iteration   2: 6.565 ops/ms
# Warmup Iteration   3: 8.153 ops/ms
Iteration   1: 8.248 ops/ms
Iteration   2: 8.141 ops/ms
Iteration   3: 7.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.073 ±(99.9%) 3.953 ops/ms [Average]
  (min, avg, max) = (7.831, 8.073, 8.248), stdev = 0.217
  CI (99.9%): [4.120, 12.026] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.138 ops/ms
# Warmup Iteration   2: 6.247 ops/ms
# Warmup Iteration   3: 7.379 ops/ms
Iteration   1: 7.611 ops/ms
Iteration   2: 7.814 ops/ms
Iteration   3: 7.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.707 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (7.611, 7.707, 7.814), stdev = 0.102
  CI (99.9%): [5.845, 9.569] (assumes normal distribution)


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
# Warmup Iteration   1: 2.121 ops/ms
# Warmup Iteration   2: 5.182 ops/ms
# Warmup Iteration   3: 6.538 ops/ms
Iteration   1: 6.736 ops/ms
Iteration   2: 6.304 ops/ms
Iteration   3: 6.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.529 ±(99.9%) 3.954 ops/ms [Average]
  (min, avg, max) = (6.304, 6.529, 6.736), stdev = 0.217
  CI (99.9%): [2.575, 10.483] (assumes normal distribution)


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
# Warmup Iteration   1: 14.569 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.005 ms/op
Iteration   1: 4.206 ±(99.9%) 0.002 ms/op
Iteration   2: 3.975 ±(99.9%) 0.005 ms/op
Iteration   3: 4.015 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.065 ±(99.9%) 2.250 ms/op [Average]
  (min, avg, max) = (3.975, 4.065, 4.206), stdev = 0.123
  CI (99.9%): [1.815, 6.315] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.707 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.773 ±(99.9%) 0.011 ms/op
Iteration   2: 3.878 ±(99.9%) 0.005 ms/op
Iteration   3: 4.091 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.914 ±(99.9%) 2.959 ms/op [Average]
  (min, avg, max) = (3.773, 3.914, 4.091), stdev = 0.162
  CI (99.9%): [0.955, 6.873] (assumes normal distribution)


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
# Warmup Iteration   1: 12.101 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.178 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.005 ms/op
Iteration   1: 4.014 ±(99.9%) 0.006 ms/op
Iteration   2: 3.947 ±(99.9%) 0.003 ms/op
Iteration   3: 3.873 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.945 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (3.873, 3.945, 4.014), stdev = 0.070
  CI (99.9%): [2.664, 5.226] (assumes normal distribution)


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
# Warmup Iteration   1: 13.323 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.784 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.181 ±(99.9%) 0.008 ms/op
Iteration   1: 4.912 ±(99.9%) 0.009 ms/op
Iteration   2: 4.719 ±(99.9%) 0.006 ms/op
Iteration   3: 4.703 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.778 ±(99.9%) 2.118 ms/op [Average]
  (min, avg, max) = (4.703, 4.778, 4.912), stdev = 0.116
  CI (99.9%): [2.660, 6.897] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.673 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.956 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.016 ms/op
Iteration   1: 3.958 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  12.124 ms/op
                 createUser·p0.9999: 25.455 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   2: 3.971 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   8.027 ms/op
                 createUser·p0.999:  25.115 ms/op
                 createUser·p0.9999: 28.179 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 3.954 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   7.352 ms/op
                 createUser·p0.999:  21.055 ms/op
                 createUser·p0.9999: 35.521 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242176
  mean =      3.961 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 772 
    [ 2.500,  5.000) = 224985 
    [ 5.000,  7.500) = 13657 
    [ 7.500, 10.000) = 1908 
    [10.000, 12.500) = 471 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     21.301 ms/op
     p(99.9900) =     32.395 ms/op
     p(99.9990) =     35.717 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 11.438 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.422 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.014 ms/op
Iteration   1: 3.805 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  21.652 ms/op
                 existUser·p0.9999: 26.396 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   2: 3.960 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.434 ms/op
                 existUser·p0.99:   8.331 ms/op
                 existUser·p0.999:  12.354 ms/op
                 existUser·p0.9999: 26.666 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.875 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   5.107 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  12.434 ms/op
                 existUser·p0.9999: 32.760 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247411
  mean =      3.879 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 439 
    [ 2.500,  5.000) = 232755 
    [ 5.000,  7.500) = 11439 
    [ 7.500, 10.000) = 1991 
    [10.000, 12.500) = 529 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     31.164 ms/op
     p(99.9990) =     33.118 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 10.891 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.643 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.016 ms/op
Iteration   1: 4.080 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   8.364 ms/op
                 getUser·p0.999:  19.938 ms/op
                 getUser·p0.9999: 30.915 ms/op
                 getUser·p1.00:   35.062 ms/op

Iteration   2: 3.996 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  14.382 ms/op
                 getUser·p0.9999: 27.328 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.904 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.309 ms/op
                 getUser·p0.999:  27.828 ms/op
                 getUser·p0.9999: 31.189 ms/op
                 getUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240491
  mean =      3.992 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 645 
    [ 2.500,  5.000) = 223047 
    [ 5.000,  7.500) = 13634 
    [ 7.500, 10.000) = 2298 
    [10.000, 12.500) = 507 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 99 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     19.874 ms/op
     p(99.9900) =     30.800 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 15.053 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.603 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.881 ±(99.9%) 0.018 ms/op
Iteration   1: 4.737 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  25.395 ms/op
                 listUser·p0.9999: 34.603 ms/op
                 listUser·p1.00:   35.324 ms/op

Iteration   2: 4.704 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   9.299 ms/op
                 listUser·p0.999:  16.612 ms/op
                 listUser·p0.9999: 23.016 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 4.557 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.015 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  20.341 ms/op
                 listUser·p0.9999: 24.642 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205783
  mean =      4.665 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 174452 
    [ 5.000,  7.500) = 25830 
    [ 7.500, 10.000) = 3988 
    [10.000, 12.500) = 817 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     22.453 ms/op
     p(99.9900) =     32.716 ms/op
     p(99.9990) =     34.923 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.777 ± 3.741  ops/ms
ClientPb.existUser                       thrpt       3   8.073 ± 3.953  ops/ms
ClientPb.getUser                         thrpt       3   7.707 ± 1.862  ops/ms
ClientPb.listUser                        thrpt       3   6.529 ± 3.954  ops/ms
ClientPb.createUser                       avgt       3   4.065 ± 2.250   ms/op
ClientPb.existUser                        avgt       3   3.914 ± 2.959   ms/op
ClientPb.getUser                          avgt       3   3.945 ± 1.281   ms/op
ClientPb.listUser                         avgt       3   4.778 ± 2.118   ms/op
ClientPb.createUser                     sample  242176   3.961 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.667           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.823           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.301           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.395           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  247411   3.879 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.128           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.832           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.665           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.164           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.406           ms/op
ClientPb.getUser                        sample  240491   3.992 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.997           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.848           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.874           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.800           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.062           ms/op
ClientPb.listUser                       sample  205783   4.665 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.128           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.453           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.716           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.324           ms/op
