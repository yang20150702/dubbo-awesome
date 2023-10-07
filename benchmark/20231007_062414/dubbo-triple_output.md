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
# Warmup Iteration   1: 1.323 ops/ms
# Warmup Iteration   2: 3.596 ops/ms
# Warmup Iteration   3: 6.614 ops/ms
Iteration   1: 6.454 ops/ms
Iteration   2: 6.772 ops/ms
Iteration   3: 6.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.531 ±(99.9%) 3.876 ops/ms [Average]
  (min, avg, max) = (6.368, 6.531, 6.772), stdev = 0.212
  CI (99.9%): [2.655, 10.407] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.974 ops/ms
# Warmup Iteration   2: 5.726 ops/ms
# Warmup Iteration   3: 6.803 ops/ms
Iteration   1: 7.225 ops/ms
Iteration   2: 7.199 ops/ms
Iteration   3: 6.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.135 ±(99.9%) 2.447 ops/ms [Average]
  (min, avg, max) = (6.981, 7.135, 7.225), stdev = 0.134
  CI (99.9%): [4.688, 9.582] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.148 ops/ms
# Warmup Iteration   2: 6.141 ops/ms
# Warmup Iteration   3: 6.729 ops/ms
Iteration   1: 6.568 ops/ms
Iteration   2: 6.561 ops/ms
Iteration   3: 6.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.454 ±(99.9%) 3.500 ops/ms [Average]
  (min, avg, max) = (6.233, 6.454, 6.568), stdev = 0.192
  CI (99.9%): [2.954, 9.955] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.747 ops/ms
# Warmup Iteration   2: 4.641 ops/ms
# Warmup Iteration   3: 5.551 ops/ms
Iteration   1: 5.614 ops/ms
Iteration   2: 5.643 ops/ms
Iteration   3: 5.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.746 ±(99.9%) 3.745 ops/ms [Average]
  (min, avg, max) = (5.614, 5.746, 5.983), stdev = 0.205
  CI (99.9%): [2.001, 9.491] (assumes normal distribution)


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
# Warmup Iteration   1: 15.611 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 5.672 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.221 ±(99.9%) 0.014 ms/op
Iteration   1: 4.984 ±(99.9%) 0.010 ms/op
Iteration   2: 4.910 ±(99.9%) 0.009 ms/op
Iteration   3: 4.682 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.859 ±(99.9%) 2.875 ms/op [Average]
  (min, avg, max) = (4.682, 4.859, 4.984), stdev = 0.158
  CI (99.9%): [1.984, 7.734] (assumes normal distribution)


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
# Warmup Iteration   1: 14.629 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.595 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.009 ±(99.9%) 0.006 ms/op
Iteration   1: 4.977 ±(99.9%) 0.006 ms/op
Iteration   2: 4.811 ±(99.9%) 0.009 ms/op
Iteration   3: 4.273 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.687 ±(99.9%) 6.711 ms/op [Average]
  (min, avg, max) = (4.273, 4.687, 4.977), stdev = 0.368
  CI (99.9%): [≈ 0, 11.398] (assumes normal distribution)


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
# Warmup Iteration   1: 14.455 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.445 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.279 ±(99.9%) 0.006 ms/op
Iteration   1: 5.176 ±(99.9%) 0.009 ms/op
Iteration   2: 4.968 ±(99.9%) 0.009 ms/op
Iteration   3: 5.003 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.049 ±(99.9%) 2.033 ms/op [Average]
  (min, avg, max) = (4.968, 5.049, 5.176), stdev = 0.111
  CI (99.9%): [3.015, 7.082] (assumes normal distribution)


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
# Warmup Iteration   1: 15.883 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.669 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.864 ±(99.9%) 0.011 ms/op
Iteration   1: 5.672 ±(99.9%) 0.016 ms/op
Iteration   2: 5.654 ±(99.9%) 0.011 ms/op
Iteration   3: 5.758 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.695 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (5.654, 5.695, 5.758), stdev = 0.056
  CI (99.9%): [4.674, 6.715] (assumes normal distribution)


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
# Warmup Iteration   1: 14.513 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.068 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.237 ±(99.9%) 0.020 ms/op
Iteration   1: 4.885 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   6.840 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  24.838 ms/op
                 createUser·p0.9999: 27.864 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   2: 4.903 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   4.571 ms/op
                 createUser·p0.90:   6.013 ms/op
                 createUser·p0.95:   6.799 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  25.251 ms/op
                 createUser·p0.9999: 82.308 ms/op
                 createUser·p1.00:   82.838 ms/op

Iteration   3: 5.084 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.159 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.234 ms/op
                 createUser·p0.95:   7.037 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  26.739 ms/op
                 createUser·p0.9999: 31.134 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 193646
  mean =      4.956 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 129062 
    [ 5.000, 10.000) = 62773 
    [10.000, 15.000) = 1273 
    [15.000, 20.000) = 208 
    [20.000, 25.000) = 119 
    [25.000, 30.000) = 171 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 7 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 10 
    [75.000, 80.000) = 6 
    [80.000, 85.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.825 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.906 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     25.199 ms/op
     p(99.9900) =     71.780 ms/op
     p(99.9990) =     82.715 ms/op
     p(99.9999) =     82.838 ms/op
    p(100.0000) =     82.838 ms/op


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
# Warmup Iteration   1: 12.333 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.236 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.709 ±(99.9%) 0.016 ms/op
Iteration   1: 4.782 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.939 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   8.822 ms/op
                 existUser·p0.999:  19.988 ms/op
                 existUser·p0.9999: 25.186 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   2: 4.926 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   6.005 ms/op
                 existUser·p0.95:   6.922 ms/op
                 existUser·p0.99:   9.601 ms/op
                 existUser·p0.999:  15.729 ms/op
                 existUser·p0.9999: 32.702 ms/op
                 existUser·p1.00:   33.030 ms/op

Iteration   3: 4.928 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   4.588 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   7.135 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  21.035 ms/op
                 existUser·p0.9999: 30.593 ms/op
                 existUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 196697
  mean =      4.878 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 157 
    [ 2.500,  5.000) = 136477 
    [ 5.000,  7.500) = 53403 
    [ 7.500, 10.000) = 5189 
    [10.000, 12.500) = 893 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.087 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     16.817 ms/op
     p(99.9900) =     31.315 ms/op
     p(99.9990) =     33.043 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 15.322 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.830 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.038 ±(99.9%) 0.019 ms/op
Iteration   1: 5.071 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.470 ms/op
                 getUser·p0.50:   4.694 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   8.004 ms/op
                 getUser·p0.99:   10.912 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 25.549 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 5.081 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.060 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.201 ms/op
                 getUser·p0.95:   7.406 ms/op
                 getUser·p0.99:   10.289 ms/op
                 getUser·p0.999:  23.036 ms/op
                 getUser·p0.9999: 25.619 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 5.069 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   4.735 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.242 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  24.115 ms/op
                 getUser·p0.9999: 32.564 ms/op
                 getUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 189016
  mean =      5.074 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 120662 
    [ 5.000,  7.500) = 58887 
    [ 7.500, 10.000) = 7149 
    [10.000, 12.500) = 1383 
    [12.500, 15.000) = 445 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.060 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     21.888 ms/op
     p(99.9900) =     29.629 ms/op
     p(99.9990) =     33.037 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 15.926 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 6.550 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.956 ±(99.9%) 0.022 ms/op
Iteration   1: 5.763 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   6.875 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.600 ms/op
                 listUser·p0.999:  27.081 ms/op
                 listUser·p0.9999: 32.458 ms/op
                 listUser·p1.00:   33.161 ms/op

Iteration   2: 5.758 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.143 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  22.442 ms/op
                 listUser·p0.9999: 26.455 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   3: 5.760 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.741 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  21.228 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 166624
  mean =      5.760 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 37721 
    [ 5.000,  7.500) = 117769 
    [ 7.500, 10.000) = 8436 
    [10.000, 12.500) = 1761 
    [12.500, 15.000) = 420 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     10.858 ms/op
     p(99.9000) =     23.618 ms/op
     p(99.9900) =     30.256 ms/op
     p(99.9990) =     33.139 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.531 ± 3.876  ops/ms
ClientPb.existUser                       thrpt       3   7.135 ± 2.447  ops/ms
ClientPb.getUser                         thrpt       3   6.454 ± 3.500  ops/ms
ClientPb.listUser                        thrpt       3   5.746 ± 3.745  ops/ms
ClientPb.createUser                       avgt       3   4.859 ± 2.875   ms/op
ClientPb.existUser                        avgt       3   4.687 ± 6.711   ms/op
ClientPb.getUser                          avgt       3   5.049 ± 2.033   ms/op
ClientPb.listUser                         avgt       3   5.695 ± 1.021   ms/op
ClientPb.createUser                     sample  193646   4.956 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.825           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.896           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.199           ms/op
ClientPb.createUser:createUser·p0.9999  sample          71.780           ms/op
ClientPb.createUser:createUser·p1.00    sample          82.838           ms/op
ClientPb.existUser                      sample  196697   4.878 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.596           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.087           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.930           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.421           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.817           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.315           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.423           ms/op
ClientPb.getUser                        sample  189016   5.074 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.060           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.496           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.404           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.888           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.629           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.358           ms/op
ClientPb.listUser                       sample  166624   5.760 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.036           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.858           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.618           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.161           ms/op
