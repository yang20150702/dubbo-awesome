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
# Warmup Iteration   1: 1.129 ops/ms
# Warmup Iteration   2: 2.419 ops/ms
# Warmup Iteration   3: 4.879 ops/ms
Iteration   1: 5.334 ops/ms
Iteration   2: 5.668 ops/ms
Iteration   3: 5.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.493 ±(99.9%) 3.063 ops/ms [Average]
  (min, avg, max) = (5.334, 5.493, 5.668), stdev = 0.168
  CI (99.9%): [2.429, 8.556] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.766 ops/ms
# Warmup Iteration   2: 4.802 ops/ms
# Warmup Iteration   3: 5.823 ops/ms
Iteration   1: 5.891 ops/ms
Iteration   2: 5.879 ops/ms
Iteration   3: 6.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.931 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (5.879, 5.931, 6.021), stdev = 0.079
  CI (99.9%): [4.492, 7.369] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.622 ops/ms
# Warmup Iteration   2: 4.528 ops/ms
# Warmup Iteration   3: 5.241 ops/ms
Iteration   1: 5.443 ops/ms
Iteration   2: 5.515 ops/ms
Iteration   3: 5.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.533 ±(99.9%) 1.827 ops/ms [Average]
  (min, avg, max) = (5.443, 5.533, 5.641), stdev = 0.100
  CI (99.9%): [3.705, 7.360] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.422 ops/ms
# Warmup Iteration   2: 3.812 ops/ms
# Warmup Iteration   3: 4.872 ops/ms
Iteration   1: 4.745 ops/ms
Iteration   2: 4.933 ops/ms
Iteration   3: 4.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.861 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (4.745, 4.861, 4.933), stdev = 0.102
  CI (99.9%): [3.007, 6.714] (assumes normal distribution)


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
# Warmup Iteration   1: 19.187 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.721 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.900 ±(99.9%) 0.017 ms/op
Iteration   1: 5.610 ±(99.9%) 0.011 ms/op
Iteration   2: 5.753 ±(99.9%) 0.009 ms/op
Iteration   3: 5.628 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.663 ±(99.9%) 1.420 ms/op [Average]
  (min, avg, max) = (5.610, 5.663, 5.753), stdev = 0.078
  CI (99.9%): [4.243, 7.083] (assumes normal distribution)


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
# Warmup Iteration   1: 18.672 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.616 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.013 ms/op
Iteration   1: 5.361 ±(99.9%) 0.008 ms/op
Iteration   2: 5.439 ±(99.9%) 0.011 ms/op
Iteration   3: 5.426 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.409 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (5.361, 5.409, 5.439), stdev = 0.042
  CI (99.9%): [4.644, 6.174] (assumes normal distribution)


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
# Warmup Iteration   1: 17.843 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.575 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.703 ±(99.9%) 0.012 ms/op
Iteration   1: 5.667 ±(99.9%) 0.019 ms/op
Iteration   2: 5.682 ±(99.9%) 0.008 ms/op
Iteration   3: 5.632 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.660 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (5.632, 5.660, 5.682), stdev = 0.025
  CI (99.9%): [5.199, 6.122] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 18.595 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.833 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.658 ±(99.9%) 0.013 ms/op
Iteration   1: 6.679 ±(99.9%) 0.018 ms/op
Iteration   2: 6.386 ±(99.9%) 0.028 ms/op
Iteration   3: 6.568 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.544 ±(99.9%) 2.699 ms/op [Average]
  (min, avg, max) = (6.386, 6.544, 6.679), stdev = 0.148
  CI (99.9%): [3.845, 9.244] (assumes normal distribution)


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
# Warmup Iteration   1: 17.237 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.045 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.119 ±(99.9%) 0.030 ms/op
Iteration   1: 5.528 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.094 ms/op
                 createUser·p0.99:   10.682 ms/op
                 createUser·p0.999:  23.744 ms/op
                 createUser·p0.9999: 28.496 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 5.693 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.523 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   8.225 ms/op
                 createUser·p0.99:   11.817 ms/op
                 createUser·p0.999:  25.199 ms/op
                 createUser·p0.9999: 28.455 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 5.576 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.796 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   7.815 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  19.229 ms/op
                 createUser·p0.9999: 31.982 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171370
  mean =      5.598 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 59721 
    [ 5.000,  7.500) = 99776 
    [ 7.500, 10.000) = 9104 
    [10.000, 12.500) = 1864 
    [12.500, 15.000) = 525 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     11.026 ms/op
     p(99.9000) =     23.827 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     33.771 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.568 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.180 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.429 ±(99.9%) 0.019 ms/op
Iteration   1: 5.544 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   7.053 ms/op
                 existUser·p0.95:   8.290 ms/op
                 existUser·p0.99:   11.502 ms/op
                 existUser·p0.999:  24.489 ms/op
                 existUser·p0.9999: 28.254 ms/op
                 existUser·p1.00:   29.229 ms/op

Iteration   2: 5.265 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  13.686 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 5.569 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.314 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   6.857 ms/op
                 existUser·p0.95:   8.356 ms/op
                 existUser·p0.99:   11.469 ms/op
                 existUser·p0.999:  25.807 ms/op
                 existUser·p0.9999: 30.450 ms/op
                 existUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175790
  mean =      5.456 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 71403 
    [ 5.000,  7.500) = 93279 
    [ 7.500, 10.000) = 8366 
    [10.000, 12.500) = 1755 
    [12.500, 15.000) = 577 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      7.963 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     18.969 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     30.948 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 18.274 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.363 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.932 ±(99.9%) 0.024 ms/op
Iteration   1: 5.906 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.540 ms/op
                 getUser·p0.50:   5.587 ms/op
                 getUser·p0.90:   7.379 ms/op
                 getUser·p0.95:   8.684 ms/op
                 getUser·p0.99:   12.009 ms/op
                 getUser·p0.999:  17.984 ms/op
                 getUser·p0.9999: 24.918 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   2: 5.927 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.676 ms/op
                 getUser·p0.95:   9.110 ms/op
                 getUser·p0.99:   12.520 ms/op
                 getUser·p0.999:  25.362 ms/op
                 getUser·p0.9999: 33.148 ms/op
                 getUser·p1.00:   34.734 ms/op

Iteration   3: 5.799 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.392 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.201 ms/op
                 getUser·p0.95:   8.143 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  27.881 ms/op
                 getUser·p0.9999: 32.096 ms/op
                 getUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163269
  mean =      5.877 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 37952 
    [ 5.000,  7.500) = 110065 
    [ 7.500, 10.000) = 11148 
    [10.000, 12.500) = 2936 
    [12.500, 15.000) = 704 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.381 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     11.895 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     34.319 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 19.420 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 7.885 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.553 ±(99.9%) 0.027 ms/op
Iteration   1: 7.145 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.603 ms/op
                 listUser·p0.50:   6.578 ms/op
                 listUser·p0.90:   9.077 ms/op
                 listUser·p0.95:   10.655 ms/op
                 listUser·p0.99:   13.763 ms/op
                 listUser·p0.999:  31.193 ms/op
                 listUser·p0.9999: 38.448 ms/op
                 listUser·p1.00:   38.994 ms/op

Iteration   2: 6.957 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.884 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   10.273 ms/op
                 listUser·p0.99:   13.713 ms/op
                 listUser·p0.999:  30.835 ms/op
                 listUser·p0.9999: 37.146 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   3: 6.776 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   8.167 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   12.795 ms/op
                 listUser·p0.999:  27.031 ms/op
                 listUser·p0.9999: 30.664 ms/op
                 listUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137949
  mean =      6.956 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 2004 
    [ 5.000,  7.500) = 107064 
    [ 7.500, 10.000) = 21612 
    [10.000, 12.500) = 5040 
    [12.500, 15.000) = 1511 
    [15.000, 17.500) = 347 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      6.521 ms/op
     p(90.0000) =      8.602 ms/op
     p(95.0000) =     10.142 ms/op
     p(99.0000) =     13.517 ms/op
     p(99.9000) =     28.837 ms/op
     p(99.9900) =     37.224 ms/op
     p(99.9990) =     38.969 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.493 ± 3.063  ops/ms
ClientPb.existUser                       thrpt       3   5.931 ± 1.438  ops/ms
ClientPb.getUser                         thrpt       3   5.533 ± 1.827  ops/ms
ClientPb.listUser                        thrpt       3   4.861 ± 1.853  ops/ms
ClientPb.createUser                       avgt       3   5.663 ± 1.420   ms/op
ClientPb.existUser                        avgt       3   5.409 ± 0.765   ms/op
ClientPb.getUser                          avgt       3   5.660 ± 0.461   ms/op
ClientPb.listUser                         avgt       3   6.544 ± 2.699   ms/op
ClientPb.createUser                     sample  171370   5.598 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.442           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.061           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.026           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.827           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.392           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  175790   5.456 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.200           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.963           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.961           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.969           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.229           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.097           ms/op
ClientPb.getUser                        sample  163269   5.877 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.939           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.381           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.667           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.895           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.674           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.113           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  137949   6.956 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.603           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.521           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.142           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.517           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.837           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.224           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.994           ms/op
