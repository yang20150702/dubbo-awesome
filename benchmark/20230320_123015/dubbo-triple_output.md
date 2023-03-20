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
# Warmup Iteration   1: 1.727 ops/ms
# Warmup Iteration   2: 4.200 ops/ms
# Warmup Iteration   3: 7.365 ops/ms
Iteration   1: 7.285 ops/ms
Iteration   2: 7.852 ops/ms
Iteration   3: 8.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.844 ±(99.9%) 10.140 ops/ms [Average]
  (min, avg, max) = (7.285, 7.844, 8.396), stdev = 0.556
  CI (99.9%): [≈ 0, 17.985] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.292 ops/ms
# Warmup Iteration   2: 6.953 ops/ms
# Warmup Iteration   3: 8.104 ops/ms
Iteration   1: 8.545 ops/ms
Iteration   2: 8.381 ops/ms
Iteration   3: 8.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.324 ±(99.9%) 4.645 ops/ms [Average]
  (min, avg, max) = (8.046, 8.324, 8.545), stdev = 0.255
  CI (99.9%): [3.679, 12.969] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 5.893 ops/ms
# Warmup Iteration   3: 7.486 ops/ms
Iteration   1: 7.908 ops/ms
Iteration   2: 8.450 ops/ms
Iteration   3: 8.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.260 ±(99.9%) 5.569 ops/ms [Average]
  (min, avg, max) = (7.908, 8.260, 8.450), stdev = 0.305
  CI (99.9%): [2.690, 13.829] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.219 ops/ms
# Warmup Iteration   2: 6.410 ops/ms
# Warmup Iteration   3: 7.250 ops/ms
Iteration   1: 7.275 ops/ms
Iteration   2: 7.159 ops/ms
Iteration   3: 6.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.106 ±(99.9%) 3.674 ops/ms [Average]
  (min, avg, max) = (6.883, 7.106, 7.275), stdev = 0.201
  CI (99.9%): [3.432, 10.780] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.517 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.007 ms/op
Iteration   1: 4.116 ±(99.9%) 0.007 ms/op
Iteration   2: 3.912 ±(99.9%) 0.008 ms/op
Iteration   3: 3.938 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.989 ±(99.9%) 2.024 ms/op [Average]
  (min, avg, max) = (3.912, 3.989, 4.116), stdev = 0.111
  CI (99.9%): [1.965, 6.012] (assumes normal distribution)


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
# Warmup Iteration   1: 11.017 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.795 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.009 ms/op
Iteration   1: 3.647 ±(99.9%) 0.008 ms/op
Iteration   2: 3.633 ±(99.9%) 0.003 ms/op
Iteration   3: 3.656 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.645 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (3.633, 3.645, 3.656), stdev = 0.011
  CI (99.9%): [3.439, 3.852] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.775 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.008 ms/op
Iteration   1: 3.763 ±(99.9%) 0.006 ms/op
Iteration   2: 3.833 ±(99.9%) 0.015 ms/op
Iteration   3: 3.961 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.852 ±(99.9%) 1.836 ms/op [Average]
  (min, avg, max) = (3.763, 3.852, 3.961), stdev = 0.101
  CI (99.9%): [2.016, 5.688] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.305 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.902 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.560 ±(99.9%) 0.015 ms/op
Iteration   1: 4.552 ±(99.9%) 0.013 ms/op
Iteration   2: 4.630 ±(99.9%) 0.013 ms/op
Iteration   3: 4.651 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.611 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (4.552, 4.611, 4.651), stdev = 0.052
  CI (99.9%): [3.662, 5.560] (assumes normal distribution)


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
# Warmup Iteration   1: 12.807 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 6.158 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.026 ms/op
Iteration   1: 3.969 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.956 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.987 ms/op
                 createUser·p0.999:  13.424 ms/op
                 createUser·p0.9999: 26.573 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   2: 3.986 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  26.733 ms/op
                 createUser·p0.9999: 32.010 ms/op
                 createUser·p1.00:   33.456 ms/op

Iteration   3: 4.097 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.886 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  29.947 ms/op
                 createUser·p0.9999: 36.962 ms/op
                 createUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238840
  mean =      4.017 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 393 
    [ 2.500,  5.000) = 222409 
    [ 5.000,  7.500) = 13603 
    [ 7.500, 10.000) = 1841 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     24.055 ms/op
     p(99.9900) =     34.480 ms/op
     p(99.9990) =     37.356 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.027 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.014 ms/op
Iteration   1: 3.930 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   8.236 ms/op
                 existUser·p0.999:  22.708 ms/op
                 existUser·p0.9999: 33.292 ms/op
                 existUser·p1.00:   34.210 ms/op

Iteration   2: 3.722 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  10.128 ms/op
                 existUser·p0.9999: 26.686 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.927 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.804 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 30.801 ms/op
                 existUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250748
  mean =      3.825 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1065 
    [ 2.500,  5.000) = 237117 
    [ 5.000,  7.500) = 9972 
    [ 7.500, 10.000) = 1803 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     31.293 ms/op
     p(99.9990) =     33.472 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 13.402 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.623 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.488 ±(99.9%) 0.019 ms/op
Iteration   1: 4.148 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.398 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   5.005 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  15.574 ms/op
                 getUser·p0.9999: 25.274 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 3.806 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.987 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  22.868 ms/op
                 getUser·p0.9999: 26.332 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.809 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  25.133 ms/op
                 getUser·p0.9999: 28.036 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245131
  mean =      3.915 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 242 
    [ 2.500,  5.000) = 232849 
    [ 5.000,  7.500) = 9355 
    [ 7.500, 10.000) = 1720 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 104 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     22.016 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     28.351 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.984 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.417 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.014 ms/op
Iteration   1: 4.515 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.411 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  24.873 ms/op
                 listUser·p0.9999: 27.879 ms/op
                 listUser·p1.00:   28.344 ms/op

Iteration   2: 4.680 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 4.994 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.699 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.538 ms/op
                 listUser·p0.999:  17.539 ms/op
                 listUser·p0.9999: 18.927 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203325
  mean =      4.721 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 160723 
    [ 5.000,  7.500) = 36072 
    [ 7.500, 10.000) = 5182 
    [10.000, 12.500) = 708 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      2.013 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     28.146 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.844 ± 10.140  ops/ms
ClientPb.existUser                       thrpt       3   8.324 ±  4.645  ops/ms
ClientPb.getUser                         thrpt       3   8.260 ±  5.569  ops/ms
ClientPb.listUser                        thrpt       3   7.106 ±  3.674  ops/ms
ClientPb.createUser                       avgt       3   3.989 ±  2.024   ms/op
ClientPb.existUser                        avgt       3   3.645 ±  0.206   ms/op
ClientPb.getUser                          avgt       3   3.852 ±  1.836   ms/op
ClientPb.listUser                         avgt       3   4.611 ±  0.949   ms/op
ClientPb.createUser                     sample  238840   4.017 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.860            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.858            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.390            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.537            ms/op
ClientPb.createUser:createUser·p0.999   sample          24.055            ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.480            ms/op
ClientPb.createUser:createUser·p1.00    sample          37.421            ms/op
ClientPb.existUser                      sample  250748   3.825 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.563            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.399            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.005            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.561            ms/op
ClientPb.existUser:existUser·p0.999     sample          14.860            ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.293            ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210            ms/op
ClientPb.getUser                        sample  245131   3.915 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.398            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.736            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.981            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.700            ms/op
ClientPb.getUser:getUser·p0.999         sample          22.016            ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.492            ms/op
ClientPb.getUser:getUser·p1.00          sample          28.443            ms/op
ClientPb.listUser                       sample  203325   4.721 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.013            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.448            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.571            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.840            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.175            ms/op
ClientPb.listUser:listUser·p0.999       sample          20.349            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.460            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.344            ms/op
