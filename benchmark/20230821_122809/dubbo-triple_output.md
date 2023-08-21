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
# Warmup Iteration   1: 1.704 ops/ms
# Warmup Iteration   2: 4.734 ops/ms
# Warmup Iteration   3: 8.037 ops/ms
Iteration   1: 8.580 ops/ms
Iteration   2: 8.632 ops/ms
Iteration   3: 8.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.729 ±(99.9%) 3.906 ops/ms [Average]
  (min, avg, max) = (8.580, 8.729, 8.974), stdev = 0.214
  CI (99.9%): [4.823, 12.635] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.488 ops/ms
# Warmup Iteration   2: 8.579 ops/ms
# Warmup Iteration   3: 9.278 ops/ms
Iteration   1: 9.061 ops/ms
Iteration   2: 9.428 ops/ms
Iteration   3: 9.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.364 ±(99.9%) 5.049 ops/ms [Average]
  (min, avg, max) = (9.061, 9.364, 9.603), stdev = 0.277
  CI (99.9%): [4.315, 14.413] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.618 ops/ms
# Warmup Iteration   2: 7.754 ops/ms
# Warmup Iteration   3: 8.734 ops/ms
Iteration   1: 9.036 ops/ms
Iteration   2: 8.878 ops/ms
Iteration   3: 9.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.011 ±(99.9%) 2.237 ops/ms [Average]
  (min, avg, max) = (8.878, 9.011, 9.119), stdev = 0.123
  CI (99.9%): [6.775, 11.248] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.431 ops/ms
# Warmup Iteration   2: 6.275 ops/ms
# Warmup Iteration   3: 7.662 ops/ms
Iteration   1: 7.640 ops/ms
Iteration   2: 7.640 ops/ms
Iteration   3: 7.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.671 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (7.640, 7.671, 7.732), stdev = 0.053
  CI (99.9%): [6.700, 8.641] (assumes normal distribution)


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
# Warmup Iteration   1: 11.985 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.005 ms/op
Iteration   1: 3.581 ±(99.9%) 0.005 ms/op
Iteration   2: 3.587 ±(99.9%) 0.009 ms/op
Iteration   3: 3.501 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.557 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.501, 3.557, 3.587), stdev = 0.048
  CI (99.9%): [2.681, 4.432] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.786 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.004 ms/op
Iteration   1: 3.431 ±(99.9%) 0.004 ms/op
Iteration   2: 3.305 ±(99.9%) 0.005 ms/op
Iteration   3: 3.333 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.356 ±(99.9%) 1.208 ms/op [Average]
  (min, avg, max) = (3.305, 3.356, 3.431), stdev = 0.066
  CI (99.9%): [2.149, 4.564] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.068 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.005 ms/op
Iteration   1: 3.569 ±(99.9%) 0.006 ms/op
Iteration   2: 3.568 ±(99.9%) 0.007 ms/op
Iteration   3: 3.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.547 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.504, 3.547, 3.569), stdev = 0.037
  CI (99.9%): [2.872, 4.222] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.393 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.547 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
Iteration   1: 4.280 ±(99.9%) 0.008 ms/op
Iteration   2: 4.085 ±(99.9%) 0.010 ms/op
Iteration   3: 4.189 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.184 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (4.085, 4.184, 4.280), stdev = 0.098
  CI (99.9%): [2.402, 5.967] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.639 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.015 ms/op
Iteration   1: 3.602 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  20.520 ms/op
                 createUser·p0.9999: 23.343 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.562 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  21.868 ms/op
                 createUser·p0.9999: 25.757 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 3.665 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.392 ms/op
                 createUser·p0.999:  22.598 ms/op
                 createUser·p0.9999: 27.215 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265888
  mean =      3.609 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4810 
    [ 2.500,  5.000) = 250992 
    [ 5.000,  7.500) = 8106 
    [ 7.500, 10.000) = 1347 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     21.339 ms/op
     p(99.9900) =     25.769 ms/op
     p(99.9990) =     28.072 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 10.547 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.011 ms/op
Iteration   1: 3.358 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  20.544 ms/op
                 existUser·p0.9999: 23.542 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   2: 3.389 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.784 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  21.335 ms/op
                 existUser·p0.9999: 24.482 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 3.441 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   7.741 ms/op
                 existUser·p0.999:  13.173 ms/op
                 existUser·p0.9999: 26.926 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282592
  mean =      3.396 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8828 
    [ 2.500,  5.000) = 266569 
    [ 5.000,  7.500) = 5283 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     13.232 ms/op
     p(99.9900) =     26.239 ms/op
     p(99.9990) =     28.350 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 11.074 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.013 ms/op
Iteration   1: 3.641 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   8.208 ms/op
                 getUser·p0.999:  21.996 ms/op
                 getUser·p0.9999: 25.730 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 3.574 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  22.327 ms/op
                 getUser·p0.9999: 26.379 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.671 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  10.437 ms/op
                 getUser·p0.9999: 28.504 ms/op
                 getUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264492
  mean =      3.628 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3278 
    [ 2.500,  5.000) = 246857 
    [ 5.000,  7.500) = 11881 
    [ 7.500, 10.000) = 1736 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 91 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     28.716 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 11.873 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.368 ±(99.9%) 0.015 ms/op
Iteration   1: 4.247 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  21.627 ms/op
                 listUser·p0.9999: 24.130 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 4.232 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 19.413 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.286 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225443
  mean =      4.255 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 211501 
    [ 5.000,  7.500) = 9927 
    [ 7.500, 10.000) = 2681 
    [10.000, 12.500) = 784 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.962 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     17.502 ms/op
     p(99.9900) =     22.902 ms/op
     p(99.9990) =     25.533 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.729 ± 3.906  ops/ms
ClientPb.existUser                       thrpt       3   9.364 ± 5.049  ops/ms
ClientPb.getUser                         thrpt       3   9.011 ± 2.237  ops/ms
ClientPb.listUser                        thrpt       3   7.671 ± 0.971  ops/ms
ClientPb.createUser                       avgt       3   3.557 ± 0.875   ms/op
ClientPb.existUser                        avgt       3   3.356 ± 1.208   ms/op
ClientPb.getUser                          avgt       3   3.547 ± 0.675   ms/op
ClientPb.listUser                         avgt       3   4.184 ± 1.782   ms/op
ClientPb.createUser                     sample  265888   3.609 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.989           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.339           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.769           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  282592   3.396 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.542           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.232           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.239           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  264492   3.628 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.774           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.612           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.001           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.836           ms/op
ClientPb.listUser                       sample  225443   4.255 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.962           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.502           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.902           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
