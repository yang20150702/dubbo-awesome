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
# Warmup Iteration   1: 0.974 ops/ms
# Warmup Iteration   2: 2.008 ops/ms
# Warmup Iteration   3: 4.957 ops/ms
Iteration   1: 5.298 ops/ms
Iteration   2: 5.571 ops/ms
Iteration   3: 5.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.466 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (5.298, 5.466, 5.571), stdev = 0.147
  CI (99.9%): [2.778, 8.154] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.464 ops/ms
# Warmup Iteration   2: 4.224 ops/ms
# Warmup Iteration   3: 5.556 ops/ms
Iteration   1: 5.662 ops/ms
Iteration   2: 5.823 ops/ms
Iteration   3: 5.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.716 ±(99.9%) 1.697 ops/ms [Average]
  (min, avg, max) = (5.662, 5.716, 5.823), stdev = 0.093
  CI (99.9%): [4.019, 7.413] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.407 ops/ms
# Warmup Iteration   2: 4.173 ops/ms
# Warmup Iteration   3: 5.359 ops/ms
Iteration   1: 5.332 ops/ms
Iteration   2: 5.394 ops/ms
Iteration   3: 5.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.411 ±(99.9%) 1.618 ops/ms [Average]
  (min, avg, max) = (5.332, 5.411, 5.507), stdev = 0.089
  CI (99.9%): [3.793, 7.029] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.476 ops/ms
# Warmup Iteration   2: 3.728 ops/ms
# Warmup Iteration   3: 4.863 ops/ms
Iteration   1: 4.819 ops/ms
Iteration   2: 4.939 ops/ms
Iteration   3: 4.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.882 ±(99.9%) 1.100 ops/ms [Average]
  (min, avg, max) = (4.819, 4.882, 4.939), stdev = 0.060
  CI (99.9%): [3.782, 5.982] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 19.849 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.736 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.905 ±(99.9%) 0.011 ms/op
Iteration   1: 5.804 ±(99.9%) 0.007 ms/op
Iteration   2: 5.776 ±(99.9%) 0.011 ms/op
Iteration   3: 5.949 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.843 ±(99.9%) 1.696 ms/op [Average]
  (min, avg, max) = (5.776, 5.843, 5.949), stdev = 0.093
  CI (99.9%): [4.147, 7.539] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.244 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.481 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.655 ±(99.9%) 0.008 ms/op
Iteration   1: 5.381 ±(99.9%) 0.011 ms/op
Iteration   2: 5.447 ±(99.9%) 0.011 ms/op
Iteration   3: 5.397 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.408 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (5.381, 5.408, 5.447), stdev = 0.034
  CI (99.9%): [4.786, 6.030] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.939 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.919 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.707 ±(99.9%) 0.007 ms/op
Iteration   1: 5.905 ±(99.9%) 0.012 ms/op
Iteration   2: 5.639 ±(99.9%) 0.016 ms/op
Iteration   3: 5.722 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.756 ±(99.9%) 2.484 ms/op [Average]
  (min, avg, max) = (5.639, 5.756, 5.905), stdev = 0.136
  CI (99.9%): [3.271, 8.240] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 20.684 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 8.303 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.905 ±(99.9%) 0.007 ms/op
Iteration   1: 6.736 ±(99.9%) 0.012 ms/op
Iteration   2: 6.427 ±(99.9%) 0.015 ms/op
Iteration   3: 6.815 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.659 ±(99.9%) 3.739 ms/op [Average]
  (min, avg, max) = (6.427, 6.659, 6.815), stdev = 0.205
  CI (99.9%): [2.921, 10.398] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.450 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.612 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.258 ±(99.9%) 0.030 ms/op
Iteration   1: 5.716 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   7.299 ms/op
                 createUser·p0.95:   8.143 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  24.909 ms/op
                 createUser·p0.9999: 30.310 ms/op
                 createUser·p1.00:   30.999 ms/op

Iteration   2: 5.785 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   5.603 ms/op
                 createUser·p0.90:   7.307 ms/op
                 createUser·p0.95:   8.176 ms/op
                 createUser·p0.99:   11.354 ms/op
                 createUser·p0.999:  16.122 ms/op
                 createUser·p0.9999: 28.137 ms/op
                 createUser·p1.00:   30.245 ms/op

Iteration   3: 5.550 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   7.053 ms/op
                 createUser·p0.95:   8.118 ms/op
                 createUser·p0.99:   10.830 ms/op
                 createUser·p0.999:  29.242 ms/op
                 createUser·p0.9999: 33.398 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168865
  mean =      5.682 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 60626 
    [ 5.000,  7.500) = 94620 
    [ 7.500, 10.000) = 10778 
    [10.000, 12.500) = 1934 
    [12.500, 15.000) = 593 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      8.151 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     31.928 ms/op
     p(99.9990) =     33.898 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.904 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.493 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.512 ±(99.9%) 0.023 ms/op
Iteration   1: 5.494 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.425 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   7.094 ms/op
                 existUser·p0.95:   8.167 ms/op
                 existUser·p0.99:   10.830 ms/op
                 existUser·p0.999:  16.777 ms/op
                 existUser·p0.9999: 25.412 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   2: 5.477 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   7.012 ms/op
                 existUser·p0.95:   8.028 ms/op
                 existUser·p0.99:   11.387 ms/op
                 existUser·p0.999:  25.255 ms/op
                 existUser·p0.9999: 28.892 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   3: 5.508 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.045 ms/op
                 existUser·p0.95:   8.094 ms/op
                 existUser·p0.99:   11.108 ms/op
                 existUser·p0.999:  27.165 ms/op
                 existUser·p0.9999: 32.316 ms/op
                 existUser·p1.00:   46.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174627
  mean =      5.493 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 78879 
    [ 5.000, 10.000) = 92820 
    [10.000, 15.000) = 2427 
    [15.000, 20.000) = 304 
    [20.000, 25.000) = 48 
    [25.000, 30.000) = 124 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.053 ms/op
     p(95.0000) =      8.094 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     24.719 ms/op
     p(99.9900) =     31.790 ms/op
     p(99.9990) =     38.952 ms/op
     p(99.9999) =     46.924 ms/op
    p(100.0000) =     46.924 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.437 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 7.352 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.181 ±(99.9%) 0.028 ms/op
Iteration   1: 5.698 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.772 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   8.249 ms/op
                 getUser·p0.99:   11.256 ms/op
                 getUser·p0.999:  23.850 ms/op
                 getUser·p0.9999: 28.239 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   2: 5.994 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.863 ms/op
                 getUser·p0.50:   5.652 ms/op
                 getUser·p0.90:   7.873 ms/op
                 getUser·p0.95:   9.060 ms/op
                 getUser·p0.99:   12.517 ms/op
                 getUser·p0.999:  18.338 ms/op
                 getUser·p0.9999: 27.164 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 5.862 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   5.538 ms/op
                 getUser·p0.90:   7.586 ms/op
                 getUser·p0.95:   8.585 ms/op
                 getUser·p0.99:   11.010 ms/op
                 getUser·p0.999:  26.968 ms/op
                 getUser·p0.9999: 30.474 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164051
  mean =      5.849 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 51605 
    [ 5.000,  7.500) = 95341 
    [ 7.500, 10.000) = 13561 
    [10.000, 12.500) = 2435 
    [12.500, 15.000) = 616 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.569 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     11.616 ms/op
     p(99.9000) =     22.736 ms/op
     p(99.9900) =     28.888 ms/op
     p(99.9990) =     33.429 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 22.181 ±(99.9%) 0.395 ms/op
# Warmup Iteration   2: 8.243 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.876 ±(99.9%) 0.034 ms/op
Iteration   1: 6.652 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.829 ms/op
                 listUser·p0.999:  27.288 ms/op
                 listUser·p0.9999: 38.666 ms/op
                 listUser·p1.00:   40.042 ms/op

Iteration   2: 6.770 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.570 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   12.747 ms/op
                 listUser·p0.999:  30.164 ms/op
                 listUser·p0.9999: 33.203 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   3: 6.789 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   9.028 ms/op
                 listUser·p0.95:   10.125 ms/op
                 listUser·p0.99:   13.025 ms/op
                 listUser·p0.999:  24.041 ms/op
                 listUser·p0.9999: 29.641 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142434
  mean =      6.736 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7307 
    [ 5.000, 10.000) = 128685 
    [10.000, 15.000) = 5690 
    [15.000, 20.000) = 364 
    [20.000, 25.000) = 195 
    [25.000, 30.000) = 120 
    [30.000, 35.000) = 62 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      6.357 ms/op
     p(90.0000) =      8.618 ms/op
     p(95.0000) =      9.814 ms/op
     p(99.0000) =     12.911 ms/op
     p(99.9000) =     27.216 ms/op
     p(99.9900) =     33.673 ms/op
     p(99.9990) =     39.764 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.466 ± 2.688  ops/ms
ClientPb.existUser                       thrpt       3   5.716 ± 1.697  ops/ms
ClientPb.getUser                         thrpt       3   5.411 ± 1.618  ops/ms
ClientPb.listUser                        thrpt       3   4.882 ± 1.100  ops/ms
ClientPb.createUser                       avgt       3   5.843 ± 1.696   ms/op
ClientPb.existUser                        avgt       3   5.408 ± 0.622   ms/op
ClientPb.getUser                          avgt       3   5.756 ± 2.484   ms/op
ClientPb.listUser                         avgt       3   6.659 ± 3.739   ms/op
ClientPb.createUser                     sample  168865   5.682 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.151           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.912           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.612           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.928           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  174627   5.493 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.028           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.136           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.053           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.094           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.719           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.790           ms/op
ClientPb.existUser:existUser·p1.00      sample          46.924           ms/op
ClientPb.getUser                        sample  164051   5.849 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.772           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.569           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.618           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.616           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.736           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.888           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  142434   6.736 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.278           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.357           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.814           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.911           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.216           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.673           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.042           ms/op
