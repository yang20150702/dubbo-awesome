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
# Warmup Iteration   1: 1.254 ops/ms
# Warmup Iteration   2: 3.004 ops/ms
# Warmup Iteration   3: 5.522 ops/ms
Iteration   1: 5.677 ops/ms
Iteration   2: 5.828 ops/ms
Iteration   3: 5.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.835 ±(99.9%) 2.942 ops/ms [Average]
  (min, avg, max) = (5.677, 5.835, 5.999), stdev = 0.161
  CI (99.9%): [2.893, 8.777] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.639 ops/ms
# Warmup Iteration   2: 4.949 ops/ms
# Warmup Iteration   3: 6.402 ops/ms
Iteration   1: 6.600 ops/ms
Iteration   2: 6.959 ops/ms
Iteration   3: 6.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.783 ±(99.9%) 3.277 ops/ms [Average]
  (min, avg, max) = (6.600, 6.783, 6.959), stdev = 0.180
  CI (99.9%): [3.506, 10.061] (assumes normal distribution)


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
# Warmup Iteration   1: 1.674 ops/ms
# Warmup Iteration   2: 5.316 ops/ms
# Warmup Iteration   3: 6.574 ops/ms
Iteration   1: 6.187 ops/ms
Iteration   2: 6.364 ops/ms
Iteration   3: 6.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.321 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (6.187, 6.321, 6.412), stdev = 0.119
  CI (99.9%): [4.157, 8.485] (assumes normal distribution)


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
# Warmup Iteration   1: 1.693 ops/ms
# Warmup Iteration   2: 4.631 ops/ms
# Warmup Iteration   3: 5.410 ops/ms
Iteration   1: 5.429 ops/ms
Iteration   2: 5.426 ops/ms
Iteration   3: 5.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.478 ±(99.9%) 1.589 ops/ms [Average]
  (min, avg, max) = (5.426, 5.478, 5.578), stdev = 0.087
  CI (99.9%): [3.889, 7.067] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 17.194 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.065 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.629 ±(99.9%) 0.006 ms/op
Iteration   1: 5.159 ±(99.9%) 0.009 ms/op
Iteration   2: 5.034 ±(99.9%) 0.009 ms/op
Iteration   3: 5.302 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.165 ±(99.9%) 2.448 ms/op [Average]
  (min, avg, max) = (5.034, 5.165, 5.302), stdev = 0.134
  CI (99.9%): [2.718, 7.613] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 14.114 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.399 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.850 ±(99.9%) 0.005 ms/op
Iteration   1: 4.889 ±(99.9%) 0.010 ms/op
Iteration   2: 4.745 ±(99.9%) 0.004 ms/op
Iteration   3: 4.799 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.811 ±(99.9%) 1.322 ms/op [Average]
  (min, avg, max) = (4.745, 4.811, 4.889), stdev = 0.072
  CI (99.9%): [3.489, 6.133] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.633 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.436 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.075 ±(99.9%) 0.007 ms/op
Iteration   1: 4.861 ±(99.9%) 0.013 ms/op
Iteration   2: 5.043 ±(99.9%) 0.009 ms/op
Iteration   3: 4.972 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.959 ±(99.9%) 1.673 ms/op [Average]
  (min, avg, max) = (4.861, 4.959, 5.043), stdev = 0.092
  CI (99.9%): [3.286, 6.632] (assumes normal distribution)


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
# Warmup Iteration   1: 19.540 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.444 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.154 ±(99.9%) 0.010 ms/op
Iteration   1: 5.711 ±(99.9%) 0.010 ms/op
Iteration   2: 5.991 ±(99.9%) 0.010 ms/op
Iteration   3: 6.099 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.934 ±(99.9%) 3.660 ms/op [Average]
  (min, avg, max) = (5.711, 5.934, 6.099), stdev = 0.201
  CI (99.9%): [2.273, 9.594] (assumes normal distribution)


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
# Warmup Iteration   1: 15.145 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.917 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.113 ±(99.9%) 0.021 ms/op
Iteration   1: 5.145 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.167 ms/op
                 createUser·p0.50:   4.899 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   9.486 ms/op
                 createUser·p0.999:  21.154 ms/op
                 createUser·p0.9999: 25.453 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 4.811 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.406 ms/op
                 createUser·p0.99:   9.224 ms/op
                 createUser·p0.999:  19.497 ms/op
                 createUser·p0.9999: 27.373 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 4.887 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.134 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.824 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  19.669 ms/op
                 createUser·p0.9999: 28.926 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 194156
  mean =      4.944 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 128 
    [ 2.500,  5.000) = 125240 
    [ 5.000,  7.500) = 62064 
    [ 7.500, 10.000) = 4864 
    [10.000, 12.500) = 1052 
    [12.500, 15.000) = 443 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.947 ms/op
     p(99.0000) =      9.903 ms/op
     p(99.9000) =     19.721 ms/op
     p(99.9900) =     28.167 ms/op
     p(99.9990) =     29.595 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 15.035 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.441 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.792 ±(99.9%) 0.017 ms/op
Iteration   1: 4.756 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.923 ms/op
                 existUser·p0.50:   4.473 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.767 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  18.929 ms/op
                 existUser·p0.9999: 27.346 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 5.010 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.843 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   7.373 ms/op
                 existUser·p0.99:   10.437 ms/op
                 existUser·p0.999:  22.679 ms/op
                 existUser·p0.9999: 34.275 ms/op
                 existUser·p1.00:   35.258 ms/op

Iteration   3: 4.989 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.690 ms/op
                 existUser·p0.999:  23.265 ms/op
                 existUser·p0.9999: 30.631 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195294
  mean =      4.915 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 133245 
    [ 5.000,  7.500) = 54622 
    [ 7.500, 10.000) = 5348 
    [10.000, 12.500) = 1123 
    [12.500, 15.000) = 424 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     22.567 ms/op
     p(99.9900) =     32.666 ms/op
     p(99.9990) =     34.946 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 14.982 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 5.586 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.518 ±(99.9%) 0.021 ms/op
Iteration   1: 5.159 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   6.250 ms/op
                 getUser·p0.95:   7.154 ms/op
                 getUser·p0.99:   11.152 ms/op
                 getUser·p0.999:  25.070 ms/op
                 getUser·p0.9999: 38.366 ms/op
                 getUser·p1.00:   39.977 ms/op

Iteration   2: 5.464 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.048 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   8.036 ms/op
                 getUser·p0.99:   10.584 ms/op
                 getUser·p0.999:  24.953 ms/op
                 getUser·p0.9999: 37.178 ms/op
                 getUser·p1.00:   38.076 ms/op

Iteration   3: 5.393 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.570 ms/op
                 getUser·p0.95:   7.471 ms/op
                 getUser·p0.99:   10.387 ms/op
                 getUser·p0.999:  26.949 ms/op
                 getUser·p0.9999: 31.714 ms/op
                 getUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179705
  mean =      5.336 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 83771 
    [ 5.000,  7.500) = 86605 
    [ 7.500, 10.000) = 6958 
    [10.000, 12.500) = 1412 
    [12.500, 15.000) = 461 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     25.208 ms/op
     p(99.9900) =     36.899 ms/op
     p(99.9990) =     39.977 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


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
# Warmup Iteration   1: 19.898 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 7.476 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.061 ±(99.9%) 0.025 ms/op
Iteration   1: 6.538 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.149 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   13.517 ms/op
                 listUser·p0.999:  28.093 ms/op
                 listUser·p0.9999: 30.711 ms/op
                 listUser·p1.00:   31.293 ms/op

Iteration   2: 5.961 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.810 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   11.191 ms/op
                 listUser·p0.999:  27.087 ms/op
                 listUser·p0.9999: 32.145 ms/op
                 listUser·p1.00:   32.637 ms/op

Iteration   3: 5.961 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.062 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  19.562 ms/op
                 listUser·p0.9999: 25.073 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156122
  mean =      6.142 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 15205 
    [ 5.000,  7.500) = 126199 
    [ 7.500, 10.000) = 10890 
    [10.000, 12.500) = 2580 
    [12.500, 15.000) = 650 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      5.825 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.776 ms/op
     p(99.9000) =     26.272 ms/op
     p(99.9900) =     31.233 ms/op
     p(99.9990) =     32.508 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.835 ± 2.942  ops/ms
ClientPb.existUser                       thrpt       3   6.783 ± 3.277  ops/ms
ClientPb.getUser                         thrpt       3   6.321 ± 2.164  ops/ms
ClientPb.listUser                        thrpt       3   5.478 ± 1.589  ops/ms
ClientPb.createUser                       avgt       3   5.165 ± 2.448   ms/op
ClientPb.existUser                        avgt       3   4.811 ± 1.322   ms/op
ClientPb.getUser                          avgt       3   4.959 ± 1.673   ms/op
ClientPb.listUser                         avgt       3   5.934 ± 3.660   ms/op
ClientPb.createUser                     sample  194156   4.944 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.876           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.947           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.903           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.721           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.167           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.212           ms/op
ClientPb.existUser                      sample  195294   4.915 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.182           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.119           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.012           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.027           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.666           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.258           ms/op
ClientPb.getUser                        sample  179705   5.336 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.741           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.569           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.600           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.208           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.899           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.977           ms/op
ClientPb.listUser                       sample  156122   6.142 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.968           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.825           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.776           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.272           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.233           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.637           ms/op
