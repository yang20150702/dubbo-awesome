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
# Warmup Iteration   1: 1.989 ops/ms
# Warmup Iteration   2: 4.931 ops/ms
# Warmup Iteration   3: 8.084 ops/ms
Iteration   1: 9.095 ops/ms
Iteration   2: 9.207 ops/ms
Iteration   3: 9.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.179 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (9.095, 9.179, 9.234), stdev = 0.073
  CI (99.9%): [7.840, 10.518] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.125 ops/ms
# Warmup Iteration   2: 8.598 ops/ms
# Warmup Iteration   3: 9.547 ops/ms
Iteration   1: 9.506 ops/ms
Iteration   2: 9.553 ops/ms
Iteration   3: 10.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.699 ±(99.9%) 5.353 ops/ms [Average]
  (min, avg, max) = (9.506, 9.699, 10.036), stdev = 0.293
  CI (99.9%): [4.346, 15.051] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.116 ops/ms
# Warmup Iteration   2: 8.432 ops/ms
# Warmup Iteration   3: 8.884 ops/ms
Iteration   1: 9.188 ops/ms
Iteration   2: 9.480 ops/ms
Iteration   3: 8.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.130 ±(99.9%) 6.958 ops/ms [Average]
  (min, avg, max) = (8.723, 9.130, 9.480), stdev = 0.381
  CI (99.9%): [2.172, 16.088] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 7.203 ops/ms
# Warmup Iteration   3: 7.749 ops/ms
Iteration   1: 7.908 ops/ms
Iteration   2: 7.786 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.914 ±(99.9%) 2.384 ops/ms [Average]
  (min, avg, max) = (7.786, 7.914, 8.047), stdev = 0.131
  CI (99.9%): [5.530, 10.298] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.323 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.008 ms/op
Iteration   1: 3.525 ±(99.9%) 0.009 ms/op
Iteration   2: 3.382 ±(99.9%) 0.014 ms/op
Iteration   3: 3.415 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.440 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (3.382, 3.440, 3.525), stdev = 0.075
  CI (99.9%): [2.073, 4.808] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.485 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.007 ms/op
Iteration   1: 3.257 ±(99.9%) 0.007 ms/op
Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
Iteration   3: 3.269 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (3.257, 3.298, 3.367), stdev = 0.061
  CI (99.9%): [2.190, 4.406] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.826 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.004 ms/op
Iteration   1: 3.381 ±(99.9%) 0.009 ms/op
Iteration   2: 3.430 ±(99.9%) 0.009 ms/op
Iteration   3: 3.441 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.417 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.381, 3.417, 3.441), stdev = 0.032
  CI (99.9%): [2.829, 4.005] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.850 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.502 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
Iteration   2: 4.009 ±(99.9%) 0.009 ms/op
Iteration   3: 3.849 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.945 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (3.849, 3.945, 4.009), stdev = 0.085
  CI (99.9%): [2.399, 5.492] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.302 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.011 ms/op
Iteration   1: 3.597 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   6.133 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  21.430 ms/op
                 createUser·p0.9999: 24.642 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   2: 3.382 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.869 ms/op
                 createUser·p0.999:  23.364 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 3.460 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  21.680 ms/op
                 createUser·p0.9999: 31.673 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275863
  mean =      3.477 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8778 
    [ 2.500,  5.000) = 256158 
    [ 5.000,  7.500) = 9365 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 152 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     21.603 ms/op
     p(99.9900) =     30.914 ms/op
     p(99.9990) =     33.391 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 9.517 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
Iteration   1: 3.449 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  22.129 ms/op
                 existUser·p0.9999: 24.501 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 3.440 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  27.361 ms/op
                 existUser·p0.9999: 32.584 ms/op
                 existUser·p1.00:   33.686 ms/op

Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  16.000 ms/op
                 existUser·p0.9999: 27.320 ms/op
                 existUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283406
  mean =      3.386 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11300 
    [ 2.500,  5.000) = 267073 
    [ 5.000,  7.500) = 4115 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     22.242 ms/op
     p(99.9900) =     31.500 ms/op
     p(99.9990) =     33.036 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 9.487 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.010 ms/op
Iteration   1: 3.707 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.505 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  13.134 ms/op
                 getUser·p0.9999: 24.391 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   2: 3.484 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  22.249 ms/op
                 getUser·p0.9999: 26.525 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.456 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.360 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  22.610 ms/op
                 getUser·p0.9999: 27.181 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270656
  mean =      3.546 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6649 
    [ 2.500,  5.000) = 253040 
    [ 5.000,  7.500) = 8873 
    [ 7.500, 10.000) = 1547 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 90 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     16.750 ms/op
     p(99.9900) =     26.671 ms/op
     p(99.9990) =     27.731 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 10.842 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.013 ms/op
Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  20.715 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   2: 4.024 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 20.188 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 3.890 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.884 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 16.565 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242465
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 234986 
    [ 5.000,  7.500) = 5289 
    [ 7.500, 10.000) = 1147 
    [10.000, 12.500) = 414 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.898 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.179 ± 1.339  ops/ms
ClientPb.existUser                       thrpt       3   9.699 ± 5.353  ops/ms
ClientPb.getUser                         thrpt       3   9.130 ± 6.958  ops/ms
ClientPb.listUser                        thrpt       3   7.914 ± 2.384  ops/ms
ClientPb.createUser                       avgt       3   3.440 ± 1.367   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 1.108   ms/op
ClientPb.getUser                          avgt       3   3.417 ± 0.588   ms/op
ClientPb.listUser                         avgt       3   3.945 ± 1.546   ms/op
ClientPb.createUser                     sample  275863   3.477 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.536           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.603           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.914           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  283406   3.386 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.108           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.242           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.686           ms/op
ClientPb.getUser                        sample  270656   3.546 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.671           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.754           ms/op
ClientPb.listUser                       sample  242465   3.958 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.898           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.936           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.099           ms/op
