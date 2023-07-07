# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.869 ops/ms
# Warmup Iteration   2: 5.162 ops/ms
# Warmup Iteration   3: 8.511 ops/ms
Iteration   1: 9.022 ops/ms
Iteration   2: 9.038 ops/ms
Iteration   3: 9.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.149 ±(99.9%) 3.783 ops/ms [Average]
  (min, avg, max) = (9.022, 9.149, 9.389), stdev = 0.207
  CI (99.9%): [5.366, 12.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.073 ops/ms
# Warmup Iteration   2: 8.904 ops/ms
# Warmup Iteration   3: 9.456 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.771 ops/ms
Iteration   3: 9.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.733 ±(99.9%) 0.820 ops/ms [Average]
  (min, avg, max) = (9.683, 9.733, 9.771), stdev = 0.045
  CI (99.9%): [8.913, 10.552] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.760 ops/ms
# Warmup Iteration   2: 8.074 ops/ms
# Warmup Iteration   3: 8.870 ops/ms
Iteration   1: 9.046 ops/ms
Iteration   2: 8.993 ops/ms
Iteration   3: 9.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.054 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (8.993, 9.054, 9.123), stdev = 0.065
  CI (99.9%): [7.868, 10.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.622 ops/ms
# Warmup Iteration   2: 7.274 ops/ms
# Warmup Iteration   3: 7.686 ops/ms
Iteration   1: 7.841 ops/ms
Iteration   2: 7.768 ops/ms
Iteration   3: 7.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.793 ±(99.9%) 0.770 ops/ms [Average]
  (min, avg, max) = (7.768, 7.793, 7.841), stdev = 0.042
  CI (99.9%): [7.023, 8.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.541 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.007 ms/op
Iteration   1: 3.413 ±(99.9%) 0.008 ms/op
Iteration   2: 3.547 ±(99.9%) 0.004 ms/op
Iteration   3: 3.421 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.460 ±(99.9%) 1.378 ms/op [Average]
  (min, avg, max) = (3.413, 3.460, 3.547), stdev = 0.076
  CI (99.9%): [2.083, 4.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 11.419 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.002 ms/op
Iteration   1: 3.253 ±(99.9%) 0.008 ms/op
Iteration   2: 3.360 ±(99.9%) 0.007 ms/op
Iteration   3: 3.608 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.407 ±(99.9%) 3.324 ms/op [Average]
  (min, avg, max) = (3.253, 3.407, 3.608), stdev = 0.182
  CI (99.9%): [0.083, 6.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.836 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.006 ms/op
Iteration   1: 3.473 ±(99.9%) 0.007 ms/op
Iteration   2: 3.444 ±(99.9%) 0.005 ms/op
Iteration   3: 3.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.470 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.444, 3.470, 3.494), stdev = 0.025
  CI (99.9%): [3.015, 3.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.881 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.007 ms/op
Iteration   1: 4.165 ±(99.9%) 0.007 ms/op
Iteration   2: 3.987 ±(99.9%) 0.016 ms/op
Iteration   3: 4.050 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.067 ±(99.9%) 1.647 ms/op [Average]
  (min, avg, max) = (3.987, 4.067, 4.165), stdev = 0.090
  CI (99.9%): [2.420, 5.715] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.679 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.022 ms/op
Iteration   1: 3.697 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  9.461 ms/op
                 createUser·p0.9999: 29.365 ms/op
                 createUser·p1.00:   31.228 ms/op

Iteration   2: 3.466 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  22.289 ms/op
                 createUser·p0.9999: 26.797 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.704 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  24.371 ms/op
                 createUser·p0.9999: 26.948 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265019
  mean =      3.619 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3412 
    [ 2.500,  5.000) = 253775 
    [ 5.000,  7.500) = 6678 
    [ 7.500, 10.000) = 697 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     21.036 ms/op
     p(99.9900) =     27.967 ms/op
     p(99.9990) =     30.551 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.585 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.009 ms/op
Iteration   1: 3.312 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  14.724 ms/op
                 existUser·p0.9999: 21.955 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   2: 3.248 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  13.954 ms/op
                 existUser·p0.9999: 26.804 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   3: 3.344 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  22.598 ms/op
                 existUser·p0.9999: 27.956 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290586
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5880 
    [ 2.500,  5.000) = 279821 
    [ 5.000,  7.500) = 3876 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     27.155 ms/op
     p(99.9990) =     28.363 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.891 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.010 ms/op
Iteration   1: 3.557 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   7.643 ms/op
                 getUser·p0.999:  19.860 ms/op
                 getUser·p0.9999: 25.366 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   2: 3.486 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.952 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  22.358 ms/op
                 getUser·p0.9999: 26.186 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.985 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  21.004 ms/op
                 getUser·p0.9999: 25.819 ms/op
                 getUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272627
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4570 
    [ 2.500,  5.000) = 259873 
    [ 5.000,  7.500) = 6540 
    [ 7.500, 10.000) = 1258 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 160 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     28.484 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.010 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.013 ms/op
Iteration   1: 4.148 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  20.573 ms/op
                 listUser·p0.9999: 25.110 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.006 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 4.047 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236131
  mean =      4.067 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 226853 
    [ 5.000,  7.500) = 6660 
    [ 7.500, 10.000) = 1901 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.849 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     24.344 ms/op
     p(99.9990) =     25.652 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.149 ± 3.783  ops/ms
ClientPb.existUser                       thrpt       3   9.733 ± 0.820  ops/ms
ClientPb.getUser                         thrpt       3   9.054 ± 1.186  ops/ms
ClientPb.listUser                        thrpt       3   7.793 ± 0.770  ops/ms
ClientPb.createUser                       avgt       3   3.460 ± 1.378   ms/op
ClientPb.existUser                        avgt       3   3.407 ± 3.324   ms/op
ClientPb.getUser                          avgt       3   3.470 ± 0.455   ms/op
ClientPb.listUser                         avgt       3   4.067 ± 1.647   ms/op
ClientPb.createUser                     sample  265019   3.619 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.762           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.036           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.228           ms/op
ClientPb.existUser                      sample  290586   3.301 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.208           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.171           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.155           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  272627   3.519 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.612           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.742           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.821           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  236131   4.067 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.344           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
