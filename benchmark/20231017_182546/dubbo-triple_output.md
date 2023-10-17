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
# Warmup Iteration   1: 1.849 ops/ms
# Warmup Iteration   2: 4.592 ops/ms
# Warmup Iteration   3: 7.244 ops/ms
Iteration   1: 7.639 ops/ms
Iteration   2: 7.869 ops/ms
Iteration   3: 7.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.751 ±(99.9%) 2.101 ops/ms [Average]
  (min, avg, max) = (7.639, 7.751, 7.869), stdev = 0.115
  CI (99.9%): [5.650, 9.851] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.063 ops/ms
# Warmup Iteration   2: 6.484 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.463 ops/ms
Iteration   2: 8.495 ops/ms
Iteration   3: 8.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.372 ±(99.9%) 3.400 ops/ms [Average]
  (min, avg, max) = (8.158, 8.372, 8.495), stdev = 0.186
  CI (99.9%): [4.972, 11.772] (assumes normal distribution)


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
# Warmup Iteration   1: 2.149 ops/ms
# Warmup Iteration   2: 6.233 ops/ms
# Warmup Iteration   3: 7.756 ops/ms
Iteration   1: 7.836 ops/ms
Iteration   2: 7.929 ops/ms
Iteration   3: 7.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.903 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (7.836, 7.903, 7.942), stdev = 0.058
  CI (99.9%): [6.843, 8.962] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.158 ops/ms
# Warmup Iteration   2: 5.493 ops/ms
# Warmup Iteration   3: 6.528 ops/ms
Iteration   1: 6.076 ops/ms
Iteration   2: 6.309 ops/ms
Iteration   3: 6.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.310 ±(99.9%) 4.273 ops/ms [Average]
  (min, avg, max) = (6.076, 6.310, 6.545), stdev = 0.234
  CI (99.9%): [2.037, 10.583] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.858 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.004 ms/op
Iteration   1: 4.189 ±(99.9%) 0.006 ms/op
Iteration   2: 3.957 ±(99.9%) 0.005 ms/op
Iteration   3: 4.157 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.101 ±(99.9%) 2.297 ms/op [Average]
  (min, avg, max) = (3.957, 4.101, 4.189), stdev = 0.126
  CI (99.9%): [1.804, 6.397] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.482 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.573 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.007 ms/op
Iteration   1: 3.936 ±(99.9%) 0.007 ms/op
Iteration   2: 4.019 ±(99.9%) 0.007 ms/op
Iteration   3: 3.908 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.954 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (3.908, 3.954, 4.019), stdev = 0.058
  CI (99.9%): [2.893, 5.016] (assumes normal distribution)


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
# Warmup Iteration   1: 14.368 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.578 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.005 ms/op
Iteration   1: 4.258 ±(99.9%) 0.005 ms/op
Iteration   2: 4.034 ±(99.9%) 0.005 ms/op
Iteration   3: 4.084 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.125 ±(99.9%) 2.142 ms/op [Average]
  (min, avg, max) = (4.034, 4.125, 4.258), stdev = 0.117
  CI (99.9%): [1.984, 6.267] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.292 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.609 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.006 ms/op
Iteration   1: 4.945 ±(99.9%) 0.009 ms/op
Iteration   2: 4.894 ±(99.9%) 0.010 ms/op
Iteration   3: 4.869 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.903 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (4.869, 4.903, 4.945), stdev = 0.038
  CI (99.9%): [4.203, 5.602] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.619 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.795 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.525 ±(99.9%) 0.019 ms/op
Iteration   1: 4.275 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.071 ms/op
                 createUser·p0.95:   6.406 ms/op
                 createUser·p0.99:   9.110 ms/op
                 createUser·p0.999:  19.928 ms/op
                 createUser·p0.9999: 22.824 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   2: 4.162 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   8.118 ms/op
                 createUser·p0.999:  13.897 ms/op
                 createUser·p0.9999: 22.686 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   3: 4.144 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   9.044 ms/op
                 createUser·p0.999:  24.795 ms/op
                 createUser·p0.9999: 29.931 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 228808
  mean =      4.193 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 746 
    [ 2.500,  5.000) = 205642 
    [ 5.000,  7.500) = 17663 
    [ 7.500, 10.000) = 3364 
    [10.000, 12.500) = 741 
    [12.500, 15.000) = 272 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     27.930 ms/op
     p(99.9990) =     30.628 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 11.647 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.013 ms/op
Iteration   1: 3.686 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.853 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   7.186 ms/op
                 existUser·p0.999:  12.544 ms/op
                 existUser·p0.9999: 24.171 ms/op
                 existUser·p1.00:   43.909 ms/op

Iteration   2: 3.871 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.825 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   8.290 ms/op
                 existUser·p0.999:  25.526 ms/op
                 existUser·p0.9999: 28.524 ms/op
                 existUser·p1.00:   32.309 ms/op

Iteration   3: 3.732 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.507 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  15.729 ms/op
                 existUser·p0.9999: 31.864 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255172
  mean =      3.762 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 244371 
    [ 5.000, 10.000) = 9872 
    [10.000, 15.000) = 626 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 84 
    [25.000, 30.000) = 123 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.850 ms/op
     p(99.9000) =     19.796 ms/op
     p(99.9900) =     31.489 ms/op
     p(99.9990) =     41.288 ms/op
     p(99.9999) =     43.909 ms/op
    p(100.0000) =     43.909 ms/op


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
# Warmup Iteration   1: 11.290 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.580 ±(99.9%) 0.018 ms/op
Iteration   1: 4.041 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  23.392 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   2: 4.090 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   8.226 ms/op
                 getUser·p0.999:  19.786 ms/op
                 getUser·p0.9999: 27.725 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 4.057 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.007 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   8.217 ms/op
                 getUser·p0.999:  27.839 ms/op
                 getUser·p0.9999: 37.618 ms/op
                 getUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236122
  mean =      4.063 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 276 
    [ 2.500,  5.000) = 218790 
    [ 5.000,  7.500) = 12917 
    [ 7.500, 10.000) = 3036 
    [10.000, 12.500) = 546 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     23.491 ms/op
     p(99.9900) =     35.480 ms/op
     p(99.9990) =     37.809 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 13.011 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.320 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.688 ±(99.9%) 0.018 ms/op
Iteration   1: 4.801 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  27.186 ms/op
                 listUser·p0.9999: 30.223 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   2: 4.684 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   3: 4.821 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  16.928 ms/op
                 listUser·p0.9999: 23.238 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201286
  mean =      4.768 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 160299 
    [ 5.000,  7.500) = 33302 
    [ 7.500, 10.000) = 6413 
    [10.000, 12.500) = 490 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.599 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      6.906 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     20.779 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     30.539 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.751 ± 2.101  ops/ms
ClientPb.existUser                       thrpt       3   8.372 ± 3.400  ops/ms
ClientPb.getUser                         thrpt       3   7.903 ± 1.059  ops/ms
ClientPb.listUser                        thrpt       3   6.310 ± 4.273  ops/ms
ClientPb.createUser                       avgt       3   4.101 ± 2.297   ms/op
ClientPb.existUser                        avgt       3   3.954 ± 1.061   ms/op
ClientPb.getUser                          avgt       3   4.125 ± 2.142   ms/op
ClientPb.listUser                         avgt       3   4.903 ± 0.699   ms/op
ClientPb.createUser                     sample  228808   4.193 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.618           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.251           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.930           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.211           ms/op
ClientPb.existUser                      sample  255172   3.762 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.507           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.850           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.796           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.489           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.909           ms/op
ClientPb.getUser                        sample  236122   4.063 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.929           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.612           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.380           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.491           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.480           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.076           ms/op
ClientPb.listUser                       sample  201286   4.768 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.599           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.426           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.031           ms/op
