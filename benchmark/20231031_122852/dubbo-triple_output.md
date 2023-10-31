# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.898 ops/ms
# Warmup Iteration   2: 2.071 ops/ms
# Warmup Iteration   3: 4.521 ops/ms
Iteration   1: 5.126 ops/ms
Iteration   2: 5.300 ops/ms
Iteration   3: 5.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.312 ±(99.9%) 3.525 ops/ms [Average]
  (min, avg, max) = (5.126, 5.312, 5.511), stdev = 0.193
  CI (99.9%): [1.787, 8.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.398 ops/ms
# Warmup Iteration   2: 4.126 ops/ms
# Warmup Iteration   3: 5.393 ops/ms
Iteration   1: 5.634 ops/ms
Iteration   2: 5.685 ops/ms
Iteration   3: 5.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.721 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (5.634, 5.721, 5.844), stdev = 0.110
  CI (99.9%): [3.721, 7.722] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.409 ops/ms
# Warmup Iteration   2: 4.286 ops/ms
# Warmup Iteration   3: 5.008 ops/ms
Iteration   1: 5.246 ops/ms
Iteration   2: 5.462 ops/ms
Iteration   3: 5.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.331 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (5.246, 5.331, 5.462), stdev = 0.115
  CI (99.9%): [3.238, 7.424] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.410 ops/ms
# Warmup Iteration   2: 3.195 ops/ms
# Warmup Iteration   3: 4.510 ops/ms
Iteration   1: 4.400 ops/ms
Iteration   2: 4.665 ops/ms
Iteration   3: 4.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.601 ±(99.9%) 3.240 ops/ms [Average]
  (min, avg, max) = (4.400, 4.601, 4.737), stdev = 0.178
  CI (99.9%): [1.360, 7.841] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.449 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 7.670 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.038 ±(99.9%) 0.016 ms/op
Iteration   1: 5.927 ±(99.9%) 0.012 ms/op
Iteration   2: 5.711 ±(99.9%) 0.013 ms/op
Iteration   3: 5.833 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.824 ±(99.9%) 1.975 ms/op [Average]
  (min, avg, max) = (5.711, 5.824, 5.927), stdev = 0.108
  CI (99.9%): [3.849, 7.798] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.436 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.847 ±(99.9%) 0.008 ms/op
Iteration   1: 5.639 ±(99.9%) 0.010 ms/op
Iteration   2: 5.594 ±(99.9%) 0.008 ms/op
Iteration   3: 5.554 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.595 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (5.554, 5.595, 5.639), stdev = 0.042
  CI (99.9%): [4.820, 6.371] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.844 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.915 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.350 ±(99.9%) 0.007 ms/op
Iteration   1: 6.233 ±(99.9%) 0.013 ms/op
Iteration   2: 5.992 ±(99.9%) 0.010 ms/op
Iteration   3: 5.806 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.010 ±(99.9%) 3.904 ms/op [Average]
  (min, avg, max) = (5.806, 6.010, 6.233), stdev = 0.214
  CI (99.9%): [2.106, 9.914] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 23.429 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.921 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.987 ±(99.9%) 0.013 ms/op
Iteration   1: 6.823 ±(99.9%) 0.012 ms/op
Iteration   2: 6.914 ±(99.9%) 0.014 ms/op
Iteration   3: 6.872 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.870 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (6.823, 6.870, 6.914), stdev = 0.046
  CI (99.9%): [6.037, 7.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 21.374 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 8.868 ±(99.9%) 0.077 ms/op
# Warmup Iteration   3: 6.502 ±(99.9%) 0.033 ms/op
Iteration   1: 5.977 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.576 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.430 ms/op
                 createUser·p0.95:   8.569 ms/op
                 createUser·p0.99:   12.272 ms/op
                 createUser·p0.999:  26.772 ms/op
                 createUser·p0.9999: 29.807 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   2: 6.032 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.569 ms/op
                 createUser·p0.95:   9.028 ms/op
                 createUser·p0.99:   12.550 ms/op
                 createUser·p0.999:  30.931 ms/op
                 createUser·p0.9999: 34.629 ms/op
                 createUser·p1.00:   35.127 ms/op

Iteration   3: 5.814 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.662 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   7.813 ms/op
                 createUser·p0.99:   10.732 ms/op
                 createUser·p0.999:  31.410 ms/op
                 createUser·p0.9999: 34.733 ms/op
                 createUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161579
  mean =      5.939 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 28699 
    [ 5.000,  7.500) = 118803 
    [ 7.500, 10.000) = 10088 
    [10.000, 12.500) = 2733 
    [12.500, 15.000) = 718 
    [15.000, 17.500) = 275 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 71 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     28.227 ms/op
     p(99.9900) =     34.517 ms/op
     p(99.9990) =     36.291 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.210 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 6.676 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.743 ±(99.9%) 0.021 ms/op
Iteration   1: 5.633 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   7.053 ms/op
                 existUser·p0.95:   8.454 ms/op
                 existUser·p0.99:   11.551 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 5.567 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.855 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   6.686 ms/op
                 existUser·p0.95:   7.758 ms/op
                 existUser·p0.99:   11.387 ms/op
                 existUser·p0.999:  27.724 ms/op
                 existUser·p0.9999: 33.022 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   3: 5.683 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.322 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   7.119 ms/op
                 existUser·p0.95:   8.217 ms/op
                 existUser·p0.99:   11.698 ms/op
                 existUser·p0.999:  28.554 ms/op
                 existUser·p0.9999: 40.894 ms/op
                 existUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170525
  mean =      5.627 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 53906 
    [ 5.000, 10.000) = 113233 
    [10.000, 15.000) = 2880 
    [15.000, 20.000) = 290 
    [20.000, 25.000) = 78 
    [25.000, 30.000) = 59 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.176 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     37.938 ms/op
     p(99.9990) =     41.627 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.984 ±(99.9%) 0.309 ms/op
# Warmup Iteration   2: 6.828 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.071 ±(99.9%) 0.024 ms/op
Iteration   1: 6.131 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.335 ms/op
                 getUser·p0.50:   5.644 ms/op
                 getUser·p0.90:   8.126 ms/op
                 getUser·p0.95:   9.781 ms/op
                 getUser·p0.99:   12.960 ms/op
                 getUser·p0.999:  19.497 ms/op
                 getUser·p0.9999: 27.387 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   2: 5.718 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.744 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   8.634 ms/op
                 getUser·p0.99:   12.966 ms/op
                 getUser·p0.999:  25.659 ms/op
                 getUser·p0.9999: 29.124 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   3: 5.740 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.867 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   6.930 ms/op
                 getUser·p0.95:   8.086 ms/op
                 getUser·p0.99:   10.928 ms/op
                 getUser·p0.999:  27.685 ms/op
                 getUser·p0.9999: 33.303 ms/op
                 getUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163822
  mean =      5.857 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 36409 
    [ 5.000,  7.500) = 112742 
    [ 7.500, 10.000) = 9950 
    [10.000, 12.500) = 3056 
    [12.500, 15.000) = 1111 
    [15.000, 17.500) = 280 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.534 ms/op
     p(99.9000) =     25.139 ms/op
     p(99.9900) =     30.399 ms/op
     p(99.9990) =     35.186 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 23.052 ±(99.9%) 0.420 ms/op
# Warmup Iteration   2: 8.414 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 7.356 ±(99.9%) 0.035 ms/op
Iteration   1: 6.838 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   6.447 ms/op
                 listUser·p0.90:   8.266 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   13.903 ms/op
                 listUser·p0.999:  27.077 ms/op
                 listUser·p0.9999: 29.840 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 6.929 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.125 ms/op
                 listUser·p0.50:   6.537 ms/op
                 listUser·p0.90:   8.274 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   13.500 ms/op
                 listUser·p0.999:  29.810 ms/op
                 listUser·p0.9999: 38.601 ms/op
                 listUser·p1.00:   38.928 ms/op

Iteration   3: 7.070 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.215 ms/op
                 listUser·p0.50:   6.644 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   10.191 ms/op
                 listUser·p0.99:   14.303 ms/op
                 listUser·p0.999:  30.233 ms/op
                 listUser·p0.9999: 35.745 ms/op
                 listUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138253
  mean =      6.944 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 1716 
    [ 5.000,  7.500) = 110772 
    [ 7.500, 10.000) = 19180 
    [10.000, 12.500) = 4161 
    [12.500, 15.000) = 1497 
    [15.000, 17.500) = 474 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.482 ms/op
     p(50.0000) =      6.545 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =      9.863 ms/op
     p(99.0000) =     14.008 ms/op
     p(99.9000) =     28.434 ms/op
     p(99.9900) =     37.432 ms/op
     p(99.9990) =     38.828 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.312 ± 3.525  ops/ms
ClientPb.existUser                       thrpt       3   5.721 ± 2.001  ops/ms
ClientPb.getUser                         thrpt       3   5.331 ± 2.093  ops/ms
ClientPb.listUser                        thrpt       3   4.601 ± 3.240  ops/ms
ClientPb.createUser                       avgt       3   5.824 ± 1.975   ms/op
ClientPb.existUser                        avgt       3   5.595 ± 0.775   ms/op
ClientPb.getUser                          avgt       3   6.010 ± 3.904   ms/op
ClientPb.listUser                         avgt       3   6.870 ± 0.833   ms/op
ClientPb.createUser                     sample  161579   5.939 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.380           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.315           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.421           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.928           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.227           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.517           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  170525   5.627 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.589           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.176           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.567           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.627           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.938           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.812           ms/op
ClientPb.getUser                        sample  163822   5.857 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.464           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.274           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.831           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.534           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.139           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  138253   6.944 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.482           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.545           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.863           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.008           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.434           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.432           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.928           ms/op
