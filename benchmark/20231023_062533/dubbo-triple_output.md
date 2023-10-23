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
# Warmup Iteration   1: 1.111 ops/ms
# Warmup Iteration   2: 2.360 ops/ms
# Warmup Iteration   3: 4.792 ops/ms
Iteration   1: 5.271 ops/ms
Iteration   2: 5.428 ops/ms
Iteration   3: 5.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.446 ±(99.9%) 3.366 ops/ms [Average]
  (min, avg, max) = (5.271, 5.446, 5.639), stdev = 0.185
  CI (99.9%): [2.080, 8.812] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.610 ops/ms
# Warmup Iteration   2: 4.396 ops/ms
# Warmup Iteration   3: 5.605 ops/ms
Iteration   1: 5.851 ops/ms
Iteration   2: 5.902 ops/ms
Iteration   3: 6.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.938 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (5.851, 5.938, 6.060), stdev = 0.109
  CI (99.9%): [3.952, 7.923] (assumes normal distribution)


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
# Warmup Iteration   1: 1.443 ops/ms
# Warmup Iteration   2: 4.285 ops/ms
# Warmup Iteration   3: 5.428 ops/ms
Iteration   1: 5.538 ops/ms
Iteration   2: 5.728 ops/ms
Iteration   3: 5.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.750 ±(99.9%) 4.090 ops/ms [Average]
  (min, avg, max) = (5.538, 5.750, 5.984), stdev = 0.224
  CI (99.9%): [1.660, 9.840] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.569 ops/ms
# Warmup Iteration   2: 4.112 ops/ms
# Warmup Iteration   3: 4.646 ops/ms
Iteration   1: 4.812 ops/ms
Iteration   2: 5.028 ops/ms
Iteration   3: 4.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.931 ±(99.9%) 1.996 ops/ms [Average]
  (min, avg, max) = (4.812, 4.931, 5.028), stdev = 0.109
  CI (99.9%): [2.935, 6.927] (assumes normal distribution)


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
# Warmup Iteration   1: 18.055 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.695 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.795 ±(99.9%) 0.010 ms/op
Iteration   1: 5.488 ±(99.9%) 0.012 ms/op
Iteration   2: 5.511 ±(99.9%) 0.012 ms/op
Iteration   3: 5.704 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.568 ±(99.9%) 2.160 ms/op [Average]
  (min, avg, max) = (5.488, 5.568, 5.704), stdev = 0.118
  CI (99.9%): [3.407, 7.728] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.720 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.572 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.767 ±(99.9%) 0.009 ms/op
Iteration   1: 5.612 ±(99.9%) 0.007 ms/op
Iteration   2: 5.461 ±(99.9%) 0.012 ms/op
Iteration   3: 5.512 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.528 ±(99.9%) 1.399 ms/op [Average]
  (min, avg, max) = (5.461, 5.528, 5.612), stdev = 0.077
  CI (99.9%): [4.129, 6.928] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.286 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.732 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.858 ±(99.9%) 0.009 ms/op
Iteration   1: 5.813 ±(99.9%) 0.010 ms/op
Iteration   2: 5.705 ±(99.9%) 0.010 ms/op
Iteration   3: 5.613 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.710 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (5.613, 5.710, 5.813), stdev = 0.100
  CI (99.9%): [3.891, 7.530] (assumes normal distribution)


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
# Warmup Iteration   1: 21.080 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 8.387 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.689 ±(99.9%) 0.013 ms/op
Iteration   1: 6.674 ±(99.9%) 0.012 ms/op
Iteration   2: 6.617 ±(99.9%) 0.015 ms/op
Iteration   3: 6.616 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.636 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (6.616, 6.636, 6.674), stdev = 0.033
  CI (99.9%): [6.030, 7.241] (assumes normal distribution)


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
# Warmup Iteration   1: 18.009 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 8.078 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.224 ±(99.9%) 0.030 ms/op
Iteration   1: 5.789 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.291 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   11.951 ms/op
                 createUser·p0.999:  29.320 ms/op
                 createUser·p0.9999: 37.646 ms/op
                 createUser·p1.00:   39.715 ms/op

Iteration   2: 5.850 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.520 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.420 ms/op
                 createUser·p0.999:  27.525 ms/op
                 createUser·p0.9999: 31.916 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   3: 5.952 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.507 ms/op
                 createUser·p0.50:   5.661 ms/op
                 createUser·p0.90:   7.602 ms/op
                 createUser·p0.95:   8.520 ms/op
                 createUser·p0.99:   11.502 ms/op
                 createUser·p0.999:  30.484 ms/op
                 createUser·p0.9999: 32.330 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163592
  mean =      5.863 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 46959 
    [ 5.000,  7.500) = 100349 
    [ 7.500, 10.000) = 12684 
    [10.000, 12.500) = 2447 
    [12.500, 15.000) = 624 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 88 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      7.496 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     11.552 ms/op
     p(99.9000) =     28.901 ms/op
     p(99.9900) =     34.032 ms/op
     p(99.9990) =     39.673 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


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
# Warmup Iteration   1: 16.839 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.036 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.680 ±(99.9%) 0.024 ms/op
Iteration   1: 5.430 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   7.086 ms/op
                 existUser·p0.95:   7.995 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  14.672 ms/op
                 existUser·p0.9999: 25.541 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   2: 5.516 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   6.988 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   11.452 ms/op
                 existUser·p0.999:  26.377 ms/op
                 existUser·p0.9999: 34.052 ms/op
                 existUser·p1.00:   35.717 ms/op

Iteration   3: 5.405 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.159 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.955 ms/op
                 existUser·p0.95:   7.840 ms/op
                 existUser·p0.99:   11.158 ms/op
                 existUser·p0.999:  29.983 ms/op
                 existUser·p0.9999: 34.996 ms/op
                 existUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176086
  mean =      5.450 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 80959 
    [ 5.000,  7.500) = 83227 
    [ 7.500, 10.000) = 9338 
    [10.000, 12.500) = 1544 
    [12.500, 15.000) = 640 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     22.396 ms/op
     p(99.9900) =     34.153 ms/op
     p(99.9990) =     36.368 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 17.539 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 7.203 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.853 ±(99.9%) 0.026 ms/op
Iteration   1: 5.683 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   3.023 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   7.504 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   11.911 ms/op
                 getUser·p0.999:  17.555 ms/op
                 getUser·p0.9999: 29.864 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   2: 5.643 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.761 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   7.184 ms/op
                 getUser·p0.95:   8.061 ms/op
                 getUser·p0.99:   11.256 ms/op
                 getUser·p0.999:  25.841 ms/op
                 getUser·p0.9999: 31.282 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   3: 5.478 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.989 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.857 ms/op
                 getUser·p0.95:   7.782 ms/op
                 getUser·p0.99:   10.584 ms/op
                 getUser·p0.999:  29.977 ms/op
                 getUser·p0.9999: 32.427 ms/op
                 getUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171320
  mean =      5.600 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 70223 
    [ 5.000,  7.500) = 87402 
    [ 7.500, 10.000) = 10525 
    [10.000, 12.500) = 2078 
    [12.500, 15.000) = 659 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 74 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.989 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.151 ms/op
     p(99.0000) =     11.403 ms/op
     p(99.9000) =     22.742 ms/op
     p(99.9900) =     31.912 ms/op
     p(99.9990) =     34.773 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 21.050 ±(99.9%) 0.384 ms/op
# Warmup Iteration   2: 8.638 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.925 ±(99.9%) 0.034 ms/op
Iteration   1: 6.792 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   8.700 ms/op
                 listUser·p0.95:   10.027 ms/op
                 listUser·p0.99:   13.945 ms/op
                 listUser·p0.999:  28.967 ms/op
                 listUser·p0.9999: 32.876 ms/op
                 listUser·p1.00:   33.391 ms/op

Iteration   2: 6.595 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   8.274 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  29.935 ms/op
                 listUser·p0.9999: 35.062 ms/op
                 listUser·p1.00:   35.258 ms/op

Iteration   3: 6.603 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   8.143 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   13.791 ms/op
                 listUser·p0.999:  25.985 ms/op
                 listUser·p0.9999: 30.593 ms/op
                 listUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143962
  mean =      6.662 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 9001 
    [ 5.000,  7.500) = 108606 
    [ 7.500, 10.000) = 20562 
    [10.000, 12.500) = 3932 
    [12.500, 15.000) = 977 
    [15.000, 17.500) = 379 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 136 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      6.283 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =      9.585 ms/op
     p(99.0000) =     13.255 ms/op
     p(99.9000) =     29.099 ms/op
     p(99.9900) =     34.460 ms/op
     p(99.9990) =     35.230 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.446 ± 3.366  ops/ms
ClientPb.existUser                       thrpt       3   5.938 ± 1.985  ops/ms
ClientPb.getUser                         thrpt       3   5.750 ± 4.090  ops/ms
ClientPb.listUser                        thrpt       3   4.931 ± 1.996  ops/ms
ClientPb.createUser                       avgt       3   5.568 ± 2.160   ms/op
ClientPb.existUser                        avgt       3   5.528 ± 1.399   ms/op
ClientPb.getUser                          avgt       3   5.710 ± 1.820   ms/op
ClientPb.listUser                         avgt       3   6.636 ± 0.605   ms/op
ClientPb.createUser                     sample  163592   5.863 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.573           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.496           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.520           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.552           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.901           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.715           ms/op
ClientPb.existUser                      sample  176086   5.450 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.012           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.897           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.879           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.396           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.153           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.814           ms/op
ClientPb.getUser                        sample  171320   5.600 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.251           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.176           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.151           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.403           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.742           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.912           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  143962   6.662 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.473           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.283           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.585           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.255           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.099           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.460           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.258           ms/op
