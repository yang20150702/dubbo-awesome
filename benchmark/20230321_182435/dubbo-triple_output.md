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
# Warmup Iteration   1: 1.787 ops/ms
# Warmup Iteration   2: 4.657 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.341 ops/ms
Iteration   2: 8.467 ops/ms
Iteration   3: 8.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.411 ±(99.9%) 1.168 ops/ms [Average]
  (min, avg, max) = (8.341, 8.411, 8.467), stdev = 0.064
  CI (99.9%): [7.243, 9.578] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.634 ops/ms
# Warmup Iteration   2: 7.417 ops/ms
# Warmup Iteration   3: 8.758 ops/ms
Iteration   1: 8.736 ops/ms
Iteration   2: 7.989 ops/ms
Iteration   3: 8.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.507 ±(99.9%) 8.216 ops/ms [Average]
  (min, avg, max) = (7.989, 8.507, 8.798), stdev = 0.450
  CI (99.9%): [0.292, 16.723] (assumes normal distribution)


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
# Warmup Iteration   1: 2.562 ops/ms
# Warmup Iteration   2: 7.495 ops/ms
# Warmup Iteration   3: 8.417 ops/ms
Iteration   1: 8.395 ops/ms
Iteration   2: 8.701 ops/ms
Iteration   3: 8.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.606 ±(99.9%) 3.337 ops/ms [Average]
  (min, avg, max) = (8.395, 8.606, 8.723), stdev = 0.183
  CI (99.9%): [5.270, 11.943] (assumes normal distribution)


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
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 6.072 ops/ms
# Warmup Iteration   3: 7.209 ops/ms
Iteration   1: 7.170 ops/ms
Iteration   2: 7.060 ops/ms
Iteration   3: 7.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.214 ±(99.9%) 3.283 ops/ms [Average]
  (min, avg, max) = (7.060, 7.214, 7.411), stdev = 0.180
  CI (99.9%): [3.931, 10.497] (assumes normal distribution)


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
# Warmup Iteration   1: 10.992 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.788 ±(99.9%) 0.007 ms/op
Iteration   2: 3.789 ±(99.9%) 0.009 ms/op
Iteration   3: 3.670 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.749 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (3.670, 3.749, 3.789), stdev = 0.068
  CI (99.9%): [2.502, 4.997] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.019 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.009 ms/op
Iteration   1: 3.586 ±(99.9%) 0.010 ms/op
Iteration   2: 3.513 ±(99.9%) 0.007 ms/op
Iteration   3: 3.423 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.507 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (3.423, 3.507, 3.586), stdev = 0.082
  CI (99.9%): [2.018, 4.996] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.198 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.008 ms/op
Iteration   1: 3.755 ±(99.9%) 0.009 ms/op
Iteration   2: 3.695 ±(99.9%) 0.008 ms/op
Iteration   3: 3.673 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.707 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (3.673, 3.707, 3.755), stdev = 0.042
  CI (99.9%): [2.935, 4.479] (assumes normal distribution)


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
# Warmup Iteration   1: 12.618 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.038 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.475 ±(99.9%) 0.008 ms/op
Iteration   1: 4.410 ±(99.9%) 0.015 ms/op
Iteration   2: 4.218 ±(99.9%) 0.019 ms/op
Iteration   3: 4.436 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.354 ±(99.9%) 2.175 ms/op [Average]
  (min, avg, max) = (4.218, 4.354, 4.436), stdev = 0.119
  CI (99.9%): [2.180, 6.529] (assumes normal distribution)


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
# Warmup Iteration   1: 12.063 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.018 ms/op
Iteration   1: 3.750 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  22.848 ms/op
                 createUser·p0.9999: 24.952 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 3.696 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.829 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 26.302 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   3: 3.688 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.250 ms/op
                 createUser·p0.999:  29.697 ms/op
                 createUser·p0.9999: 32.834 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 258628
  mean =      3.711 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1112 
    [ 2.500,  5.000) = 251624 
    [ 5.000,  7.500) = 4717 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     32.215 ms/op
     p(99.9990) =     33.586 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 10.275 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.010 ms/op
Iteration   1: 3.664 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.823 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.638 ms/op
                 existUser·p0.999:  23.093 ms/op
                 existUser·p0.9999: 30.048 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   2: 3.702 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   7.062 ms/op
                 existUser·p0.999:  12.193 ms/op
                 existUser·p0.9999: 26.414 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.614 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  24.740 ms/op
                 existUser·p0.9999: 29.594 ms/op
                 existUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 262182
  mean =      3.659 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1220 
    [ 2.500,  5.000) = 251134 
    [ 5.000,  7.500) = 8119 
    [ 7.500, 10.000) = 1227 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.825 ms/op
     p(99.9000) =     19.637 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     30.565 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 12.598 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.011 ms/op
Iteration   1: 3.731 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.812 ms/op
                 getUser·p0.999:  24.642 ms/op
                 getUser·p0.9999: 29.636 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   2: 3.612 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  12.603 ms/op
                 getUser·p0.9999: 25.002 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 3.701 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  26.837 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 260696
  mean =      3.681 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1137 
    [ 2.500,  5.000) = 250026 
    [ 5.000,  7.500) = 8092 
    [ 7.500, 10.000) = 977 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     23.603 ms/op
     p(99.9900) =     29.292 ms/op
     p(99.9990) =     30.765 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 12.654 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.016 ms/op
Iteration   1: 4.601 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  26.134 ms/op
                 listUser·p0.9999: 28.708 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 4.632 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  17.100 ms/op
                 listUser·p0.9999: 20.387 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.434 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.085 ms/op
                 listUser·p0.999:  19.166 ms/op
                 listUser·p0.9999: 20.925 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 210722
  mean =      4.554 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 185459 
    [ 5.000,  7.500) = 20644 
    [ 7.500, 10.000) = 3693 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     29.160 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.411 ± 1.168  ops/ms
ClientPb.existUser                       thrpt       3   8.507 ± 8.216  ops/ms
ClientPb.getUser                         thrpt       3   8.606 ± 3.337  ops/ms
ClientPb.listUser                        thrpt       3   7.214 ± 3.283  ops/ms
ClientPb.createUser                       avgt       3   3.749 ± 1.248   ms/op
ClientPb.existUser                        avgt       3   3.507 ± 1.489   ms/op
ClientPb.getUser                          avgt       3   3.707 ± 0.772   ms/op
ClientPb.listUser                         avgt       3   4.354 ± 2.175   ms/op
ClientPb.createUser                     sample  258628   3.711 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.055           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.744           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.215           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  262182   3.659 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.055           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.596           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.637           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.655           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.835           ms/op
ClientPb.getUser                        sample  260696   3.681 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.171           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.603           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.292           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  210722   4.554 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.990           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.300           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.344           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
